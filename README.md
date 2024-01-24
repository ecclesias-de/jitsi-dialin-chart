### Building a the chart
A chart is build for every merge request. Its version is 0.0.0-<short commit sha>. It is pushed to the gitlab docker registry: oci://dockerregistry.metaways.net/se/jitsi-dialin-chart/chart/jitsi-dialin.
This version is intended for development and testing

To build a release create a tag. With to following syntax: chart-<semantic version> eg. chart-2.0.0-rc1+build10
This chart will also be pushed to the gitlab docker registry