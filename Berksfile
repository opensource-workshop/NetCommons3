source 'https://api.berkshelf.com'

cookbook 'boilerplate'
cookbook 'boilerplate_php'
cookbook 'composer', git: 'https://github.com/Morphodo/chef-composer.git'
cookbook 'netcommons', git: 'https://github.com/NetCommons3/chef_netcommons.git'
cookbook 'php', git: 'https://github.com/trinitronx/php.git', branch: 'COOK-4439-add-php-5.5.9-support-on-ubuntu-12.04'

group :development do
  # cookbook 'boilerplate', path: '../topaz2/cookbooks/boilerplate'
  # cookbook 'boilerplate_php', path: '../topaz2/cookbooks/boilerplate_php'
  # cookbook 'netcommons', path: '../chef_netcommons'
  cookbook 'boilerplate', git: 'https://github.com/topaz2/chef_boilerplate.git'
  cookbook 'boilerplate_php', git: 'https://github.com/topaz2/chef_boilerplate_php.git'
end
