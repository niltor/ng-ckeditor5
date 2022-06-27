ng-ckeditor5-classic
========================================
Build for angular editor!

- simple upload adapter
- code and codeblock
- markdown support 

# Usage
1. Add typings.d.ts file in your project!
```typescript
declare module 'ng-ckeditor5-classic' {
    const ClassicEditor: any;
    export = ClassicEditor;
}
```

2. import as editor
```typescript
import * as ClassicEditor from 'ng-ckeditor5-classic';

```
3. define variable
```typescript
public editor: CKEditor5.EditorConstructor = ClassicEditor;
```
