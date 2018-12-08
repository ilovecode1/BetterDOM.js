BetterDOM's CDN https://cdn.jsdelivr.net/gh/ilovecode1/BetterDOM.js@master/betterdom.min.js

# Documentation

##Inner HTML

###Set

####Before

```
document.getElementById("ID").innerHTML = "HTML";
```

####After

```
i("ID").set("HTML");
```

##Body

###Set

####Before

```
var get = document.getElementById("ID").innerHTML;
```

####After

```
var get = i("ID").get();
```

#Docs End Here!
