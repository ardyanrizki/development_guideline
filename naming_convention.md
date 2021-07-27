## 1. Folder Structure
   > Folder stucture should be simple and highly maintainable. Avoid multi nesting and naming the file with descriptive class/naming system instead.
   
   #### **Single-nest folder**  
   |- 📁 pages  
   |- 📁 components  
   |- 📁 api  
   |- 📁 public  
   |- 📁 styles  
   |- 📁 theme  

To import file module use `@<folder-name>/<file-name>`
## 2. File Naming
  
  > In case you missed universal type case convention: `camelCase` `PascalCase` `kebab-case` `snake_case` `Dot.Case`

  ### Project Name `kebab-case`
      
      booku-<clientweb/serverweb>-<optional:class/class>-<version>
      
  **Example**
  - Client:  
      `booku-clientweb-v1.0`
      
  - Server:  
      `booku-serverweb-v1.0`
  
  ### Pages `kebab-case`
      <routing-name>.tsx
  Always use `kebab-case`. As url, it allows best practice for SEO.
  
  ### Components `Capitalize.Dot.Case`  
      <AtomicStructure>.<ComponentName>.<optional:PageOrParentName>.tsx
  
  Atomic structure:
  1. `Atom`
  2. `Molecule`
  3. `Organism`
  4. `Template`
  
  Utility:
  1. `Layout`
  2. `Input`

  ### API `kebab-case`
      api.<file-name>.<extension>
 
  ### Theme & Styles `kebab-case`
      <file-name>.<extension>
 
  ### Public & Static Files `snake-case`
      <file_name>.<extension>
