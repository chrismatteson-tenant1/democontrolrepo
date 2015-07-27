# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#
# Brief example:
#
#   mod 'puppetlabs/stdlib', '4.1.0'
#
# The default production environment for the SE Team is just going to pull in
# the current version of our "profile" module from the Forge and whatever
# dependencies it has.

forge "https://forgeapi.puppetlabs.com"

# PL Modules

mod 'puppetlabs/java', '1.3.0'
mod 'puppetlabs/git', '0.3.0'
mod 'puppetlabs/dism', '1.1.0'
mod 'puppetlabs/reboot', '0.1.9'
mod 'puppetlabs/registry', '1.0.3'
mod 'puppetlabs/acl', '1.1.0'
mod 'puppetlabs/apache', '1.5.0'
mod 'puppetlabs/pe_gem', '0.1.0'
mod 'puppetlabs/vcsrepo', '1.2.0'
mod 'puppetlabs/stdlib', '4.5.1'
mod 'puppetlabs/powershell', '1.0.4'
mod 'puppetlabs/ntp', '3.3.0'
mod 'puppetlabs/concat', '1.2.0'
mod 'puppetlabs/firewall', '1.4.0'
mod 'puppetlabs/inifile', '1.2.0'
mod 'puppetlabs/mysql', '3.3.0'
mod 'puppetlabs/pe_puppetserver_gem', '0.0.1'
mod 'puppetlabs/aws', '1.0.0'
mod 'puppet/windows_firewall', '1.0.0'
mod 'puppetlabs/splunk', '3.1.1'
mod 'puppetlabs/tomcat', '1.3.1'

# Community Modules

mod 'stahnma/epel', '1.0.2'
mod 'opentable/iis', '1.3.0'
mod 'opentable/windowsfeature', '1.0.0'
mod 'seteam/profile', '0.4.6'
mod 'seteam/role', '1.1.1'
mod 'nanliu/staging', '1.0.3'
mod 'hunner/wordpress', '1.0.0'
mod 'lwf/remote_file', '1.0.1'

# TSE modules - either maintained under seteam or by individual SE's

mod 'tsefacts',
  :git => 'https://github.com/mrzarquon/puppet-tse_facts.git'
mod 'ldap',
  :git => 'https://github.com/mrzarquon/puppet-ldap.git'
mod 'tse_admins',
  :git => 'https://github.com/mrzarquon/puppet-tse_admins.git'
mod 'tse_awsnodes',
  :git => 'https://github.com/mrzarquon/puppet-tse_awsnodes.git'
mod 'tse_windows',
  :git => 'https://github.com/mrzarquon/puppet-tse_windows.git'
mod 'ec2tags',
  :git => 'https://github.com/mrzarquon/puppet-ec2tags.git'

# SAMPLE APP:
mod 'sampleapp',
  :git => 'https://github.com/chrismatteson/puppet-sampleapp.git'
