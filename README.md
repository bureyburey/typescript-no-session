# typescript-script-no-session-storage
Script tag support for TypeScript

## Based on
<a href="https://github.com/basarat/typescript-script">https://github.com/basarat/typescript-script</a>

## Usage
Add the following lines at the bottom of your page: 
```html
<script src="https://rawgit.com/Microsoft/TypeScript/master/lib/typescriptServices.js"></script>
<script src="https://rawgit.com/bureyburey/typescript-no-session/master/transpiler_no_session_storage.js"></script>
```

And then you can use script tags that load `.ts` files or even have `typescript` inline: 
```html
<script type="text/typescript" src="script.ts"></script>
<script type="text/typescript">
    setTimeout(()=>console.log('hello'));
</script>
```
