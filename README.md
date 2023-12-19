Hi Murali Garapati
 - yes, this is expected as it was existing behaviour. This ticket was only scoped to make sure the buffer changes were preserved and not lost. If we would like the buffer to be drawn to the drawn geo specifically, we'll need a separate improvement ticket. I would suggest we also identify if we want the buffer drawn to both geo's, or if the original geo should be removed altogteher similar to 3D maps.


Hi Murali - the "duplicate" should behave the same as if you were to go to the item's interactions and select duplicate. When you duplicate via this method Title, Description, and Created attributes are the same as the original item being duplicated, and the modified date has the duplication time until it is updated again. I have added a comment in the description, stating that the "Duplicate" from "Add to space" should behave the same as the "Duplicate" from the item's interactions.
