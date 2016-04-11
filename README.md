# maintenance

This a simple maintenance page for Cloud Foundry. It uses staticfile_buildpack to always return 503 and an error page.
It uses a wildcard route (https://docs.cloudfoundry.org/adminguide/manage-domains-routes.html#create-wildcard-route) to handle requests for any non-existing or stopped application.
