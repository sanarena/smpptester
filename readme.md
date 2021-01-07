## A quick and dirty SMPP Tester wrapper using nodejs.

### To install it:
```
npm i
chmod +x smpp
ln -s $(pwd)/smpp /usr/local/bin  
```

### To run it:
```
ip=smpp.example.com protocol=smpp port=2675 user=demo pass=test dest=100000000 msg=hello\ world ./smpp
```

### for SMPP over SSL:
```
ip=smpp.example.com protocol=ssmpp port=8445 user=demo pass=test dest=100000000 msg=hello\ world ./smpp
```