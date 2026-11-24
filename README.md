# GDIM 31 Final: 2D
## Devlogs

### Milestone 1

1. Technical Problem and Solution

While working on my final project, I noticed that the cat could push items just by walking into them. This was not what I wanted because the main mechanic of my game was kicking items. At first, I thought there was something wrong with my kicking script. However, I realized that the problem was actually related to the colliders. I created separate layers for the player and the items and changed their settings in the Physics 2D Layer Collision Matrix. I also kept the kick colliders separate from the player’s body. In the Kickable script, I used AddForce() with ForceMode2D.Impulse inside the Kick() method. After testing several times, I was able to make the items move when kicked instead of being pushed by the cat.

I also had some trouble making the checklist. The checklist did not appear at first, and Unity showed an error. After checking the HUD in the Inspector, I found that the checklist prefab was missing. I created my own prefab with two images, one for the item and one for the checkmark. I then connected it to the HUD and used a List to keep track of the required items. The KickedItem() method helped update the checklist when the player kicked an item. I was happy when the checkmarks finally appeared correctly. This experience helped me understand how important it is to check the connections between scripts and GameObjects, rather than only looking for problems in the code. 




### Milestone 2
TODO.

## Playtesting Reports
### Milestone 1
#### Report 1
TODO.

#### Report 2
TODO.

### Milestone 2
#### Report 1
TODO.

#### Report 2
TODO.

## Open-Source Assets
- [Interior sprites](https://rcpstd.itch.io/interior-tileset-asset-pack-16x16)
- [Ninja cat sprites](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://ghostpixxells.itch.io/pixelfood)
- [More food and item sprites](https://ipixl.itch.io/pixel-art-items-part-1)
