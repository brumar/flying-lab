# Notes

The output are often a deception. Note that it makes reference to the imagery technique

# PROMPT

This technique works like the technique "Imagery" but attempt to merge with multiples images in one scene.

The goal here is to produce a scene that tie concepts together.
The expected output is as such.

    image for concept A. Explain what it illustrates
        sub-concept 1. Explain what it illustrates
        sub-concept 2. Explain what it illustrates
        ....
        scene composition: describe a scene that involves all the images.
    image for concept B. Explain what it illustrates.
        sub-concept 1. Explain what it illustrates
        sub-concept 2. Explain what it illustrates
        ....
        scene composition: describe a scene that involves all the images.

To achieve this output, you need to follow these instructions:

First generate a mindmap of the content that is only one level deep.
The parent nodes are the key concepts, the children nodes are the sub-concepts. Ensure that a parent has between 2 and 5 children. Never more than 5 children.

Just like the Imagery technique, key concepts will be transformed into images. Then you will do the same for sub-concents.
Finally, for each key concept, you will describe a simple scene that involves the image for the key concept and its sub-concepts

It's important that images are strongly connected, don't do a patchwork.
Possible interactions are:

    morphing : one image is partially morphed into another
    interaction: images interact together, make it vivid.
    composition: one image is physically attached to the other

Describe this scene then ask the user if he wants to use Dall-e to produce an image. It's important to chunk the knowledge so that a scene has between 2 and 5 images. if there are more than 5 subnodes in the mindmap, cut it in two parts. Your output will be as follow :

This is of outmost importance to respect as much as possible these two constraints :

    the scene must be as simple as possible.
    the images in the scene must be as connected as possible.
    Focus on specific, visually representable elements. Describe actions and scenarios rather than abstract concepts. Avoid ambiguous language that could be interpreted as including text.
    the style must be of simple drawings.

once the scene are described, ask the user if he wants a dall-e output for a scene in particular. Respect strongly the composition you wrote.
