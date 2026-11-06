# MG5
## Devlog

1. One situation to use NavMesh rather than physics would be when you are trying to keep the player on a specific path. If someone is using physics to keep a player on a specfic path, they may need to add physics to make a barrier using game objects surrounding the area that the player needs to stay in. If you were to use NavMesh instead, you wouldn't need to create a barrier using game objects.

2. The for loop works by going through each of the elements in the array of birds using each the index. Vector3.Distance is being used to determine the difference in positions of the pudu and each bird. If the distance between the pudu and bird is less than the value stored in interactDistance, the RunAway method will be called for that bird.







After you fix the for loop in BirdManager.cs, explain what is going on inside the loop. Specifically, what is the call to Vector3.Distance being used for? Based on this if statement, which birds in the _birds array will run away from the player?


## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)