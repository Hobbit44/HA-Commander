# HA-Commander
Search, and interact with Home Assistant from Wox


# How-To:

### Basics:

Begind by typing the defualt ActionWord: "ha"

This will bring up a list allowing you to filter all entities by service.

You can filter by services listed below:

* group
* automation 
* device_tracker 
* sensor
* switch 
* zone 
* sun 
* light 
* switch 
* media_player 
* binary_sensor 
* device_tracker 
* persistent_notification

#### Example:

```ha light```

```ha automation```

Of course just typing will list _ALL_ entities narrowed by your search query.

### Interaction:

Selecting an entity will toggle it by default.

Activating a light entity will toggle it on and off.

While activating a media player will toggle play and pause.

### Advanced:

Typing an entities full "friendly_name" or if no friendly_name, "entity_id" will bring up contextural results according to that entities service. You may also display the entities attributes.

