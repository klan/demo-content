# \<demo-content\>

## Installation

``` bash
bower install demo-content --save
```

## Usage

``` json
{
  "header": "On the road again",
  "headerImage": "https://getmdl.io/templates/blog/images/road_big.jpg",
  "body": "**Excepteur reprehenderit sint exercitation ipsum consequat qui sit id velit elit. Velit anim eiusmod labore sit amet. Voluptate voluptate irure occaecat deserunt incididunt esse in. Sunt velit aliquip sunt elit ex nulla reprehenderit qui ut eiusmod ipsum do.**\n\nQui ullamco consectetur aute fugiat officia ullamco proident Lorem ad irure. Sint eu ut consectetur ut esse veniam laboris adipisicing aliquip minim anim labore commodo. Incididunt eu enim enim ipsum Lorem commodo tempor duis eu ullamco tempor elit occaecat sit. Culpa eu sit voluptate ullamco ad irure. Anim commodo aliquip cillum ea nostrud commodo id culpa eu irure ut proident. Incididunt cillum excepteur incididunt mollit exercitation fugiat in. Magna irure laborum amet non ullamco aliqua eu. Aliquip adipisicing dolore irure culpa aute enim. Ullamco quis eiusmod ipsum laboris quis qui.",
  "author": {
    "name": "Klaus Nielsen",
    "mail": "hello@kriss-kross.io",
    "image": "https://cdn0.iconfinder.com/data/icons/user-pictures/100/male-128.png"
  }
}
```
``` html
<link rel="import" href="bower_components/demo-content/demo-block.html">

<demo-block
  header="[[json.header]]"
  header-image="[[json.headerImage]]"
  body="[[json.body]]"
  author="[[json.author]]"></demo-block>
```

## Setup

### Prerequisites

Install [npm](https://www.npmjs.com/) (or install [Node](https://nodejs.org/en/download/)):

``` bash
curl -L https://www.npmjs.com/install.sh | sh
```

Install [bower](https://bower.io/):

``` bash
npm install -g bower
```

### Tools

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

``` bash
npm install -g polymer-cli
```

### Start the development server

This command serves the app at `http://localhost:8080/components/demo-content/` and provides basic URL
routing for the app:

``` bash
polymer serve
```
