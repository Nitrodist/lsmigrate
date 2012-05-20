## About

This small bash script will take the files it is passed and make them slightly more legible to read.

To install, just throw the lsmigrate file into your PATH somewhere, make sure you can execute it (chmod +x) and then you can start using it.

## Before

```shell
mark@linux-qmbm:~/rubyapps/fat_free_crm/db/migrate> ls * | cat
20100928030598_create_sessions.rb
20100928030599_create_users.rb
20100928030600_create_openid_tables.rb
20100928030601_create_accounts.rb
20100928030602_create_permissions.rb
20100928030603_create_settings.rb
20100928030604_create_preferences.rb
20100928030605_create_campaigns.rb
20100928030606_create_leads.rb
20100928030607_create_contacts.rb
20100928030608_create_opportunities.rb
20100928030609_create_account_contacts.rb
20100928030610_create_account_opportunities.rb
20100928030611_create_contact_opportunities.rb
```

## After!

```shell
mark@linux-qmbm:~/rubyapps/fat_free_crm/db/migrate> lsmigrate *
Pretty Date                   Ugly Date                  Text

2010-09-28 03:05:98           20100928030598             create sessions
2010-09-28 03:05:99           20100928030599             create users
2010-09-28 03:06:00           20100928030600             create openid tables
2010-09-28 03:06:01           20100928030601             create accounts
2010-09-28 03:06:02           20100928030602             create permissions
2010-09-28 03:06:03           20100928030603             create settings
2010-09-28 03:06:04           20100928030604             create preferences
2010-09-28 03:06:05           20100928030605             create campaigns
2010-09-28 03:06:06           20100928030606             create leads
2010-09-28 03:06:07           20100928030607             create contacts
2010-09-28 03:06:08           20100928030608             create opportunities
2010-09-28 03:06:09           20100928030609             create account contacts
2010-09-28 03:06:10           20100928030610             create account opportunities
2010-09-28 03:06:11           20100928030611             create contact opportunities
```
