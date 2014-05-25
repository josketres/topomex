# topomex


Popular topology encoding formats for maps of Mexico.

* topojson ([https://github.com/mbostock/topojson])

## Maps
* mx-states - `dist/mx_states.topo.json`

## Examples
* datamaps + mx-states ([http://rawgit.com/josketres/topomex/master/examples/datamaps-mx_states.html])

## Build (generate the maps data yourself)

### Dependencies
* Vagrant
* Virtualbox

### Build

    git clone 
    cd topomex/vagrant
    vagrant up
    vagrant ssh
    /topomex/scripts/create_mx_states_json.sh
