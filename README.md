# Vuejs 3 + Parcel 2

This repository was made after finding the docs for creating new projects with Vuejs 3 and Parcel 2 a little confusing.

### The issue

Installing the dependencies from the beginning won't work. It will require you to reinstall Parcel.

### The solution

After the `yarn.lock`is generated, reinstall Parcel.

`yarn add -D parcel@next`

Or when using NPM run:

`npm install -D parcel@next`

### TL;DR

If you clone this project with my `yarn.lock`, it will work. But if you install all the dependencies by deleting the lock beforehand, it won't.
