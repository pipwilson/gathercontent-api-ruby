This is a simple Ruby wrapper around the GatherContent API.

Download and then:

1. add your API key as an environment variable. You can get this from `https://YOUR_SUBDOMAIN.gathercontent.com/settings/api`
2. replace 'philwilson' in the line starting `api = GatherContentApi.new` with whatever your GatherContent subdomain is - API calls are restricted by API key and subdomain!
3. Run these commands:

~~~~
$ gem install httparty
$ gem install hashie
$ ruby gathercontent-api-client.rb
~~~~

and you're done!

[HTTParty](http://httparty.rubyforge.org/) is an awesome HTTP client.

Hashie gives us [Mash](https://github.com/intridea/hashie#mash), which helps us convert Hashes (including nested hashes) into objects.


