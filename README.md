"# charts" 
# Add repo before using
$ helm repo add helm-wind https://raw.githubusercontent.com/phonginreallife/charts/master/
"wind" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo wind
NAME                	CHART VERSION	APP VERSION	DESCRIPTION
phonginreallife/...	0.1.0        	1.0.0      	A Helm chart for Kubernetes

# Get configurations (values file)
$ helm show values phonginreallife/... > myvalues.yaml

# Install chart with your configurations
$ helm install <your install name here > phonginreallife/...
