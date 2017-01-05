# onos_restconf
onos restconf application

# set up
## 1
vi ~/onos/modules.defs

'//apps/restconf:onos-apps-restconf-oar',

## 2
vi ~/onos/apps

<module>restconf</module>

# build:

tools/build/onos-buck build onos

# test:

tools/build/onos-buck test