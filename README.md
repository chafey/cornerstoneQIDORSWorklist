cornerstoneQIDORSWorklist
=========================

This project contains a prototype/example worklist for querying via QIDO-RS.  It will issue a QIDO-RS Studies query
to the specified QIDO-RS Root URL with the filter criteria and show the results.

You can access this application live [here](https://rawgit.com/chafey/cornerstoneQIDORSWorklist/master/src/index.html)

This worklist has been verified to work properly against the
[Orthanc DICOMWeb implementation](https://github.com/chafey/orthanc-vagrant) using a CORS proxy.  You can find information
about other [DICOMWeb implementations here](https://github.com/chafey/dicomWeb).

If you need a CORS proxy, try this:

https://www.npmjs.com/package/corsproxy

and use it like this to talk to a DICOMWeb QIDO-RS on http://localhost:8042/qido-rs/studies

http://localhost:9292/localhost:8042/qido-rs/studies