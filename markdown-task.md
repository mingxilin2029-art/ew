Welcome to **TreeLife**, your guide to learning about the beauty diversing, and importance of treees arond the world 
---
# About Us 

At **TreeLife**, we're passionate about forests and green living 
our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects

"The best time to plant a tree was 20 years ago, The second best time is now"
-chinese proverb
---

# Featured Trees 
## Oak Tree

**scientific Name:** Quercus robur

<img src="https://sites.dartmouth.edu/dujs/files/2020/11/EL-1.png"/>
Known fir its strength and longevity, the oak is a symbol of endurance.
---

# Pine Tree
**scintific Name:** *Pinus*
Evergreen and aromatic, pine trees thrive in colder regions.
<img src="https://www.sciencing.com/sciencing/do-pine-trees-need-survive-6549613/c64512e361624e3d9a21ffc39aed7f5c.jpg" alt="What Do Pine Trees Need To Survive?"/>

# Tree Identification Tool 
You can use this simple **Javascript** function to identify a tree by its characteristice:

function identify_tree(leaf_shape, region){
    
    if(leaf_shape == "needle" && region == "cold"){
    
        } else if (leaf_shape  == "broad" && region == "temperate"){
    
            return "Oak Tree"
    
        } else {
    
            return "unknown Tree"
        }
}

**console**.log(identify_tree("needle","cold"))