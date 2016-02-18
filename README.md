---
name: "ed-example-element"
status: Experimental
people: 
  - role: Product Owner
    name: John Doe
    email: "john.doe@pearson.com"
  - role: Designer
    name: Eve Example
    email: "eve.example@pearson.com"
implementations: 
  - type: Origami
    url: "http://origami.pearsoned.com/example"
dependencies: 
  - "ed-typography@v^1.0.0"
  - "ed-buttons@^1.0.0"
prose: 
  siteurl: "https://ndarville.github.io"
  metadata: 
    ./: 
      - name: layout
        field: 
          element: hidden
          value: post
      - name: categories
        field: 
          element: hidden
          value: blog
      - name: title
        field: 
          element: text
      - name: date
        field: 
          element: hidden
      - name: excerpt
        field: 
          element: text
          placeholder: Use 200 characters at most.
      - name: id
        field: 
          element: hidden
      - name: tags
        field: 
          element: hidden
published: true
---



# element-template
A blank template to start a new element definition. Edit this README.md file to define your element. See the [Element Definition Guide](www.example.com) for tips on writing a good definition.

You can include images by adding them to the `/images` folder. Downloadable files (such as a `.sketch` or `.ai` mockup) should be stored in the `/downloads` folder.

Making a change
