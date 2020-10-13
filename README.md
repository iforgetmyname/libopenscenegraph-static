# libopenscenegraph-static
Static library build for OpenSceneGraph(http://www.openscenegraph.org)


## OSG version 3.6.4 for Ubuntu 18.04 LTS
Configured with following cmake options:
```bash
cmake -DBUILD_OSG_APPLICATIONS:BOOL="0" \
      -DDYNAMIC_OPENTHREADS:BOOL="0" \
      -DDYNAMIC_OPENSCENEGRAPH:BOOL="0"
```

Built following modules:
```bash
make OpenThreads osg osgDB osgGA osgText osgUtil osgViewer
```

