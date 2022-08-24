# Functions
* [sleep](#sleep)
* [wear](#wear)
* [drop](#drop)
* [enter](#enter)
* [warp](#warp)
* [punch](#punch)
* [wrench](#wrench)
* [place](#place)
* [move](#move)
* [say](#say)
* [sendPacket](#sendPacket)
* [collectSet](#collectSet)
* [collect](#collect)
* [connect](#connect)
* [disconnect](#disconnect)
* [addBot](#addBot)
* [removeBot](#removeBot)
* [findPath](#findPath)
* [findItem](#findItem)
* [httpGet](#httpGet)


## sleep
`sleep(ms)`

Example:
```lua
sleep(200)
```

## wear
`wear(id)`

Example:
```lua
wear(48)
```

## drop
`drop(id)` or `drop(id,count)`

Example:
```lua
drop(2)
drop(2,200)
```

## enter
`enter()`

Example:
```lua
enter()
```

## warp
`warp(world name)`

Example:
```lua
warp("START")
```

## punch
`punch(x,y)`

Example:
```lua
punch(0,1)
```

## wrench
`wrench(x,y)`

Example:
```lua
wrench(0,1)
```

## place
`place(id,x,y)`

Example:
```lua
place(2,0,1)
```

## move
`move(radiusx,radiusy)`

Example:
```lua
move(0,1)
```

## say
`say(text)`

Example:
```lua
say("Hello World")
```

## sendPacket
`sendPacket(type,packet)`

Example:
```lua
sendPacket(3,"action|quit")
```

## collectSet
`collectSet(collect,radius)`

Example:
```lua
collectSet(true,3)
```

## collect
`collect(radius)`

Example:
```lua
collect(3)
```

## connect
`connect()`

## disconnect
`disconnect()`

## addBot
`addBot(name,password)`

Example:
```lua
addBot("GrowX", "GrowX1")
```

## removeBot
`removeBot(name)`

Example:
```lua
removeBot("GrowX")
```

## findPath
`findPath(x,y)` or `findPath(x,y,delay)`

Example:
```lua
findPath(0,0)
```
or
```lua
findPath(0,0,100)
```

## findItem
`findItem(id)`

Example:
```lua
print(findItem(2))
```

## httpGet
`httpGet(link)`

Example:
```lua
print(httpGet("https://raw.githubusercontent.com/IniTyoo/GrowX-Docs/main/README.md"))
```


