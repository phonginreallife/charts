"# charts" 
# Add repo before using
$ helm repo add helm-wind https://raw.githubusercontent.com/phonginreallife/charts/master/

"helm-wind" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo wind

# Get configurations (values file)
$ helm show values helm-wind/to-do-app > myvalues.yaml

# Install chart with your configurations
$ helm install <your install name here> helm-wind/to-do-app
