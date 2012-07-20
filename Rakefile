PUPPETMASTER = 'puppet.maksit.com.au'
SSH = 'ssh -t -A'
task :deploy do
sh "git push"
sh "#{SSH} #{PUPPETMASTER} 'cd /etc/puppet && git pull'"
end

