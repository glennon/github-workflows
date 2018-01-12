Cheat Sheet for Transcompiling JavaScript ES6 to ES5 with Babel

1. From your main directory, initialize in shell with `npm init`. This will ask some questions to describe the project, as well as create a *package.json* file.

2. Create a directory for original .js code called **src**

3. Install babel dependencies. Side note: After running these commands, the dependencies will be added to the *devDependencies* property in *package.json*.
```shell
npm install babel-cli -D
npm install babel-preset-env -D
```

4. Create a *.babelrc* file (`touch .babelrc`) and insert this text into it:  
```javascript
{
  "presets": ["env"]
}
```

4. Add the following key-value pair to the scripts object in *package.json*. By the way, do not forget to add a comma between this and any other key-value pairs in the script object.  
```javascript
"build": "babel src -d lib"
```

5. Run `npm run build` to transcompile your code from **src** (original ES6 code). The resulting ES5 code will be in the **lib**  directory.
