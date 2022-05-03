<div align="center">

# Sazeh
A front-end UI generator and component loader for web applications.

</div>

   ‌

## Table of Contents

- [Getting Started](#getting-started)
- [How Sazeh works](#how-sazeh-works)
   - [Constructor (Sazeh Saz)](#constructor-sazeh-saz)
   - [Component (Sazeh)](#component-sazeh)
   - [Instructions](#instructions)
- [License](#license)


   ‌

## Getting Started
Sazeh is a tool for arranging and structuring web pages from the **server side**. You can learn more about how to use this tool by reading the rest of this document step by step

   ‌
   
## How Sazeh works
Sazeh consists of a **constructor (Sazeh Saz)**, a set of **components (Sazeh)**, and a **Instructions**. The task of the constructor (Sazeh Saz) is to put the components (Sazeh) together depending on what Instructions (JSON) specifies.  

   ‌

### Constructor (Sazeh Saz)
The task of the **constructor (Sazeh Saz)** is to put together and build a complete web page using **components (Sazeh)**. The **constructor (Sazeh Saz)** uses the **Instructions** as the map and uses it to figure out exactly where each **component (Sazeh)** will be located.

   ‌

### Component (Sazeh)
**Component (Sazeh)** is the smallest part of each page. In fact, each web page is a collection of components (Sazeh) in different combinations.

   ‌

### Instructions
The **Instructions (JSON)** is sent from the server and tells the **Sazeh Saz** where and how to place each **Sazeh**. Below you can see an example of Instructions in JSON format.

   ‌

```JSON
{
  "id": "c0",
  "type": "SAZEH_SLIDER",
  "attrs": {
    "loop": true
  },

  "children": [
    {
      "id": "c01",
      "type": "SAZEH_IMAGE",
      "attrs": {
        "image": "#",
        "alt": "Image 1"
      },

      "children": []
    }
  ]
}
```

   ‌

## License
This project is licensed under the MIT license.
