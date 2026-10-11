# minigame 2
### Devlog


### 1. Issue I encountered and how I fixed it:

The if statement in Step 2. The statement was missing parentheses around the condition, it would cause a compiler error. I corrected it to if (_timeLeft <= 0.0f), and this allows the spell to disappear when its timer reaches zero.


### 2. What I think this line of code means:

I think _spriteRenderer.color = new Color(r, 0.2f, 0.2f); changes the color of an object in Unity. The period is used to access something that belongs to an object, like the color of the SpriteRenderer. The word new creates a new Color value. I think the three values represent red, green, and blue, and changing r changes how much red is in the object's color.


## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
