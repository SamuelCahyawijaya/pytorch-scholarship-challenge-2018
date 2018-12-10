# PyTorch Udacity Showcase
Github page for PyTorch Udacity album showcase

# Adding new artwork
### Fork the repository
Fork this repository on https://github.com/SamuelCahyawijaya/samuelcahyawijaya.github.io

### Add new artwork metadata 
Modify `data.json` adding new element into the top-level array
```
    {
        "title" : "<Title>",
        "author" : "<Author>",
        "country" : "<Country>",
        "content" : {
            "image" : "<Content Image URL>",
            "caption" : "<Content Image Caption>"
        },
        "style" : {
            "image" : "<Style Image URL>",
            "caption" : "<Style Image Caption>"
        },
        "fuse" : {
            "image" : "<Result Image URL>",
            "caption" : "<Result Image Caption>"
        }
    }
```

If you can't provide a publicly available image url, you can add your image to `./images` folder and use relative path on the `image` field as shown in the example below
```
{
    "title" : "Apocalypse",
    "author" : "Samuel",
    "country" : "Indonesia",
    "content" : {
        "image" : "./images/c7.png",
        "caption" : "Venice"
    },
    "style" : {
        "image" : "./images/s7.jpg",
        "caption" : "Scream - Edvard Munch"
    },
    "fuse" : {
        "image" : "./images/r7.png",
        "caption" : "Is this the end?"
    }
}
```

**Notes** : Please use JPG image and resize the image properly with maximum image size at most 800kB in order to maintain the size of the repository to be as small as possible.

### Send pull request
Commit & push your change and then send a pull request

### Wait for the approval
I will try to approve all the pull requests within 24 hours. Just ping me on Slack if I haven't approved the pull request.
