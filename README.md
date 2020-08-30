# savereload - allow developers to easily reload their resources.

this resource will restart any resource if there is a change in any files inside of it.

**Note: This only works with files ending in `.js, .lua, .dll` at the moment, but can be changed to add more if needed.**

### Ensure you add these 3 ace permissions into your config to ensure this works correctly.

```cfg
add_ace resource.savereload command.ensure allow
add_ace resource.savereload command.start allow
add_ace resource.savereload command.stop allow
```

Also make sure that the `resource` section matches the name of the resource in your `resources` folder, else it will not function properly.