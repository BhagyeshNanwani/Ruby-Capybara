# Ruby-Capybara
Simple Repository Using Selenium WebDriver With Ruby-Capybara

STEP 1: Add in your BROWSERSTACK_USERNAME and BROWSERSTACK_ACCESSKEY in the config files.
Alternatively you can
You can export the environment variables for the Username and Access Key of your BrowserStack account

export BROWSERSTACK_USERNAME=<browserstack-username> &&
export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>


STEP 2: To install in all the dependencies : bundle install

STEP 3: To run feature files in parallel, I have created task named all inside the Rakefile and i have passed in those profiles that I wished to execute in parallel
Command that could be used for execution of that profile is : rake -m all
