# Hooking
* [addHook](#addhook)

## addHook
`addHook(fname,name,function)`

Example For Varlist:
```lua
addHook("onvariant", "hook_var", function(var)
print("got call " .. var[0])
end)
addHook("onrawpacket", "hook_raw", function(packet)
print("got raw type  " .. packet.type)
end)
```

## RemoveHook
`removeHook(name)`
`removeHooks()` Remove all hooks
