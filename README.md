# WOD Template ICS 314

Purpose: I felt like it was too time consuming to do the following for WOD assignments: 

- Create a repository 
- Download the files in the WOD assignment and put them in the newly created repository
- Verify that everything works

After the **setup** is completed, could we then work on the WOD assignment, which would waste valuable time on completing the programming challenges if things like eslint didn't work. 

With that being said, I created this template as a way to speed up the process to creating new repositories and ensuring that everything works. I am **assuming** that the following files are consistent for the WODs: 

- `.eslintrc.js`
- `.eslintignore`
- `.gitignore`
- `package.json`
- `tsconfig.json`

# Steps

1. Go to this page: [https://github.com/LeviKuhaulua/wod-template/tree/main]()
2. Click on `Use this template` > `Create a new repository`
3. Configure repo to however you like 
4. Clone to your machine
5. Edit this README to follow format (if any) for WODs
6. Rename the `rename.ts` file 
    - make sure to edit the `src` attribute in the `script` tag of the index.html file! 

## Useful Function

Added a script called `build` in the *package.json* file to compile any typescript files. If you want to use it then run the following in the terminal `npm run build`
