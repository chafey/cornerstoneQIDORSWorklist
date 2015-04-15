cornerstoneQIDORSWorklist
=========================

This project contains a prototype/example worklist for querying via QIDO-RS and was created during the SIIM 2014
hackathon to help me understand QIDO-RS.  It will issue a QIDO-RS Studies query to the specified QIDO-RS Root URL
with the filter criteria and show the results.  If you click a study, an instances query is run, but the results
are not displayed (yet).  It would be nice to do display series and instance level information somehow, pull
requests are welcome!


If you have access to a DICOMWeb implementation, you can try out the QIDO-RS live in your browser
[here](http://rawgit.com/chafey/cornerstoneQIDORSWorklist/master/src/index.html) by updating the QIDO-RS Root URL.
The live version is setup to run "out of the box" against a local [orthanc-vagrant VM](https://github.com/chafey/orthanc-vagrant)
using a [CORS proxy](https://www.npmjs.com/package/corsproxy).  You can find information
about other DICOMWeb Implementations [here](https://github.com/chafey/dicomWeb).


