# Recipes

## Setup (8)

- [opsworks_initial_setup][1]
- [ssh_host_keys][2]
- [ssh_users][3]
- [mysql::client][4]
- [dependencies][5]
- [ebs][6]
- [opsworks_ganglia::client][7]
- [mod_php5_apache2][8]

## Configure (5)

- [opsworks_ganglia::configure-client][16]
- [ssh_users][2]
- [mysql::client][4]
- [agent_version][9]
- [php::configure][10]

## Deploy (2)

- [deploy::default][11]
- [deploy::php][12]

## Undeploy (1)

- [deploy::php-undeploy][13]

## Shutdown (2)

- [opsworks_shutdown::default][14]
- [apache2::stop][15]

[1]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/opsworks_initial_setup/recipes/default.rb
[2]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/ssh_host_keys/recipes/default.rb
[3]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/ssh_users/recipes/default.rb
[4]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/mysql/recipes/client.rb
[5]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/dependencies/recipes/default.rb
[6]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/ebs/recipes/default.rb
[7]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/opsworks_ganglia/recipes/client.rb
[8]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/mod_php5_apache2/recipes/default.rb
[9]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/agent_version/recipes/default.rb
[10]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/php/recipes/configure.rb
[11]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/deploy/recipes/default.rb
[12]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/deploy/recipes/php.rb
[13]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/deploy/recipes/php-undeploy.rb
[14]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/opsworks_shutdown/recipes/default.rb
[15]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/apache2/recipes/stop.rb
[16]: https://github.com/aws/opsworks-cookbooks/blob/release-chef-11.10/opsworks_ganglia/recipes/configure-client.rb
