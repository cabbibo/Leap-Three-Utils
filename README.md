Three.js Utils for Leap

leapToScene( position , frame , size )

  takes in a leap position, and outputs a THREE.Vector3 
  scaled so the interaction box corresponds to a cube
  that is of dimensions 'size'

leapToDom( position , frame , w , h )

  takes in a leap position, and outputs an array of [x,y]
  that makes the interaction box correspond to the entire
  size of the DOM window ( in DOM coordinantes )

leapToScreen( position , frame , w , h )

  same as leapToDom , but coordinates are in 'three space',
  origin center , up as positive y direction

