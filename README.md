# onos_restconf
onos restconf application

build:
tools/build/onos-buck build onos
test:
tools/build/onos-buck test

vi ~/onos/modules.defs
'//apps/restconf:onos-apps-restconf-oar',