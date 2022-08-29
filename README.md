# uzi

## Traits

The uzi is a small, one handed automatic machine gun. When using the .metaversefile, sounds effects, visual effects on bullet collision.

## How to place the uzi in your world

1. Navigate to the .metaversefile and find the 'raw' button
2. Copy the link to the raw file
3. Open your .scn file
4. Add add the raw .metaversefile link to a new object by creating a "start_url" field. \n Here's an example:

```json
{
    "start_url": "https://raw.githubusercontent.com/webaverse/uzi/master/.metaversefile",
}
```

5. In order to see it, you'll likely want to add a position with the "position" tag and rotation with the "quaternion" tag. You can find an example in the uzi.scn file.