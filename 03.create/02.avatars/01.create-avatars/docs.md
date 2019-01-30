---
title: Create Your Own Avatar
taxonomy:
    category: docs
---

There are two ways to create your own avatar: you can either create your own from scratch using 3D modeling tools such as Adobe Fuse, Mixamo, and Blender, or you can download an existing avatar from external sources such as TurboSquid or CGTrader. 

>>>>>If you get an avatar from an external source such as TurboSquid or CGTrader, it is likely that the skeleton does not match our [avatar standards](./avatar-standards). To use these avatars with High Fidelity, use the [High Fidelity Avatar Exporter for Unity](../find-avatars) to correctly map the skeleton and package your avatar. 

If you want to create an avatar from scratch, this page covers the steps needed to create, rig, and package your avatar. 

**On This Page:**
* [Create an Avatar from Scratch](#create-an-avatar-from-scratch)
* [Package Your Avatar](#package-your-avatar)
* [Community Tools for Avatars](#community-tools-for-avatars)

## Create an Avatar from Scratch

The steps involved in creating your avatar are:

1. Create an avatar with 3D character modeling tool such as Adobe Fuse, Blender or Maya. 
2. Rig and animate your avatar with an animation tool such as Mixamo.
3. Fine tune your avatar using a tool such as Blender or Maya.
4. Package the model in High Fidelity for use as an avatar.  

Check out this YouTube playlist for one way to create and customize your own avatar. Here, we use Adobe Fuse to create our avatar, Mixamo to rig our avatar automatically, and Blender to adjust the rendering on our avatar. We also have written instructions on the same process: 

* [Create an Avatar with Fuse](../fuse-tutorial)
* [Rig Your Avatar in Mixamo](../mixamo-tutorial)
* [Modify Materials and Textures with Blender](../blender-tutorial)

[plugin:youtube](https://www.youtube.com/watch?v=6NfiH4rdVRM)

## Package Your Avatar

Once you've created your avatar, you need to create an FST file to accompany your FBX model. This process is called *packaging your avatar*. Once you've packaged your avatar, you need to [host it in the cloud](../host-avatar) or on our Marketplace before using it in High Fidelity.

We've created the **Avatar Packager** to create an FST file for you. In addition, you can use the Avatar Packager to host your avatar on the Marketplace, edit an existing avatar package, and put it on. 

To package your avatar using the Avatar Packager:

1. In Interface, go to **Edit > Avatar Packager**. 
2. In the Avatar Packager window that opens, click 'New Project'.
3. In the Create Project window, fill in the following details:
   * Name: The name you want for your avatar. 
   * Project Location: The folder path where your avatar's files are stored. The Avatar Packager will create a new folder for your project at this location, which will include your FBX model, an FST file, and any scripts/textures in your avatar.
   * Avatar Model: Your avatar's FBX file.
   * Texture Folder: If your avatar has textures in a separate folder, specify the folder location. If your avatar's textures are embedded in the FBX, you do not need to specify anything. 
4. Click 'Create'.

At this point, you have successfully packaged your avatar. If you host your avatar on the cloud, you can close the Avatar Packager here and upload your FST file and FBX model to your cloud location. 

If you want to sell your avatar on the Marketplace or upload it to High Fidelity's servers, continue using the Avatar Packager:
 
1. Click 'Upload' to upload your avatar's files to High Fidelity's servers. If you make any changes to your custom avatar, you will need to update it through this packager to see your changes. To update, select your project and click 'Open Project' in step 1. Follow the same steps to update your avatar.
2. Once your avatar is uploaded to the servers, click 'View in Inventory' to view your custom avatar. ![](inventory.png)
3. Click 'Wear' to try out your new avatar! 
4. You can view your avatar in the Marketplace. It is currently in Draft mode. You will need to submit it for review to make your avatar available for purchase on the Marketplace.

## Community Tools for Avatars
As you're creating your avatar, remember that High Fidelity is an open-source project. Many of our community members have created plug-ins, add-ons, toolkits, skeletons and more to help you create content, including avatars. Here are a few for you to play around with.

### [Blender Add-on by Menithal](https://github.com/Menithal/Blender-Hifi-Addon)

Plugin ("Project Hermes") is a plugin for Blender to allow for easier content creation and importing for the High Fidelity Metaverse Platform. It features: 

- **Material Tools**: Allows for easier pipeline to apply materials to objects so that they are ready to use in High Fidelity.
- **Armature Tools**: Adds a skeleton that is compatible with High Fidelity and let you configure bone names for use in advanced scripts.
- **Avatar Converters**: Translates and fixes models and materials from MMD and Mixamo so that they work in High Fidelity.
- **Export Tools**: Exports avatars and scenes so that they can be used in High Fidelity.
- **Import Tools**: Imports primitive entities from High Fidelity so that you can make modifications to them.

Install it here: [https://github.com/Menithal/Blender-Hifi-Addon](https://github.com/Menithal/Blender-Hifi-Addon)

---
Have a project you've been working on that you'd like us to share? Let us know by editing this page in GitHub! 


**See Also**

+ [Find and Use an Existing Avatar](../find-avatars)
+ [Host Your Avatar](../host-avatar)