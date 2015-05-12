### How to add new event?

1. Copy draft into posts folder ```cp _drafts/YEAR-MONTH-DAY-kaunasphp-vNUMBER.markdown _posts/2015-05-12-kaunasphp-v99.markdown```
2. Update placeholders in name, event_url and content
3. Update other things, if neccessary (things going after talks and a blank line will appear only for the latest event) 
4. Commit and push to github (it will rebuild blog on server side)

### How to run this website on local machine?

(prerequisites: have project cloned and ruby installed on your machine)

1. Install bundler gem (if you don't have yet) ```gem install bundler```
2. Install project dependencies ```bundle install --path='.gems'```
3. Run jekyll server ```bundle exec jekyll serve```
