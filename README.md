### Clone of rtlamr

see [https://github.com/bemasher/rtltcp](https://github.com/bemasher/rtltcp)

this is just some mods i've made so it will compile and save data off to GCP

####To build
`go build .`
should do it.  

then run it with something like:  
`./rtlamr-pi -format=json -filterid=3806796,65560195 -server=192.168.0.110:1234`