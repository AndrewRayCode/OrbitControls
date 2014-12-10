OrbitControls
-------------

This is a RequireJS / Browserify compatible fork of OrbitControls. See
[the THREE.js example](http://threejs.org/examples/#misc_controls_orbit) for
how it behaves.

This library does NOT modify the THREE object. The original OrbitControls
defines this addon as "THREE.OrbitControls". This fork does not and leaves it
as its own object.

Usage
-----

    var OrbitControls = require('OrbitControls.js');
    var controls = new OrbitControls( camera, domElement );

Additionally, this library defines a `destroy` method to remove the control
bindings from the DOM element and window.

    controls.destroy();
