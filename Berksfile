source "https://supermarket.getchef.com"
cookbook 'mysql'
group :integration do
  cookbook 'java'
#  cookbook 'minitest-handler'
#  cookbook 'stash_test', :path => 'test/cookbooks/stash_test'
end

recipe 'stash', 'Installs/Configures Atlassian Stash'
recipe 'stash::apache2', 'Installs/Configures Apache 2 proxy for Stash'
recipe 'stash::backup_client', 'Installs/Configures Atlassian Stash Backup Client'
recipe 'stash::backup_client_cron', 'Installs/Configures Atlassian Stash Backup Client cron.d'
recipe 'stash::configuration', "Configures Stash's settings"
recipe 'stash::database', 'Installs/configures MySQL/Postgres server, database, and user for Stash'
recipe 'stash::linux_standalone', 'Installs/configures Stash via Linux standalone archive'
recipe 'stash::service_init', 'Installs/configures Stash init service'
recipe 'stash::tomcat_configuration', "Configures Stash's built-in Tomcat"