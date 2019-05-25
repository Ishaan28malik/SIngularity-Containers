$ singularity pull shub://vsoch/hello-world   # pull with default name, vsoch-hello-world-master.simg <br/>
$ singularity pull --name hello.simg shub://vsoch/hello-world   # pull with custom name<br/>

**Docker Image**<br/>
$ singularity pull docker://godlovedc/lolcow  # with default name<br/>
$ singularity pull --name funny.simg docker://godlovedc/lolcow # with custom name<br/>
