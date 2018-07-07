# OpenPackageManagerRepository

## How to add my own package to the list?
- you need to have a github repository for your asset.
- your github repository should not be a Unity project. it sould only contain your package data.
you can compare [a valid repository](https://github.com/omid3098/OpenAudio) with [an invalid](https://github.com/omid3098/OpenWatcher) one

![image](https://user-images.githubusercontent.com/6388730/42286418-10a8bf78-7fc8-11e8-94e7-318a7afa3525.png)

- create new issue with these info:

issue title: [NewPackage] Package name
issue content: 

anything you want to say + repository github link + this Json:

```
        {
            "name": "Package display name",
            "description": "Package description",
            "packageName": "Github repository name",
            "version": "Latest released version in github",
            "author": "Your Github username"
        }
```
Example: 
```
        {
            "name": "Open Audio",
            "description": "An easy to use audio manager for unity",
            "packageName": "OpenAudio",
            "version": "1.0.0",
            "author": "omid3098"
        }
```

[Check sample issue](https://github.com/omid3098/OpenPackageManagerRepository/issues/1)
