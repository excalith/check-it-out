<p align="center">
	<h1 align="center">Check It Out</h1>
</p>
<p align="center">
	<img src="https://github.com/jwu910/check-it-out/raw/master/docs/assets/images/checkit-intro.gif">
</p>

<p align="center">
	<a href="https://travis-ci.org/jwu910/check-it-out">
		<img alt="Build Status" height="18" src="https://travis-ci.org/jwu910/check-it-out.svg?branch=master">
	</a>
	<a href="https://www.npmjs.org/package/check-it-out">
		<img alt="Downloads per week" height="18" src="https://img.shields.io/npm/dw/localeval.svg">
	</a>
	<a href="https://badge.fury.io/js/check-it-out">
		<img alt="npm version" height="18" src="https://badge.fury.io/js/check-it-out.svg">
	</a>
	<a href="https://badge.fury.io/gh/jwu910%2Fcheck-it-out">
		<img alt="GitHub version" height="18" src="https://badge.fury.io/gh/jwu910%2Fcheck-it-out.svg">
	</a>
	<a href="https://twitter.com/intent/tweet?text=Check%20out%20this%20project%20on%20Github%20https://github.com/jwu910/check-it-out">
		<img src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social">
	</a>
</p>

<hr/>

Check it out, before you checkout.

Check It Out lets you interactively see and choose what branch you want to check out without the hassle of trying to type out a long or confusing branch name. Checking out branches just got even simpler!

## Requirements
[Node >= v4.0](https://nodejs.org/en/blog/release/v4.0.0/)

[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Required for core features

## Installation
We're on [NPM!](https://www.npmjs.org/package/check-it-out)
```
npm install -g check-it-out
```

#### Installing from source
[Fork](https://github.com/jwu910/check-it-out#fork-destination-box) or clone the repository
```
git clone https://github.com/jwu910/check-it-out.git
```

Navigate to your repository directory and run
```
npm install
```

Create a symbolic link to the entry point

###### Linux/Mac:
In the repository directory run:
```
npm link
```

## Usage
Run this command to list local and remote branches!
```
checkit
```

![Check It Out Usage](docs/assets/images/checkit-usage.gif)

Call git log on current highlighted branch with `[space]`

![Quick Git Log!](docs/assets/images/checkit-log.gif)


| Commands | Description |
| -------- | ------------ |
|`j/k, down/up`| Navigate the list |
|`h/l, left/right`| Previous/Next remote |
|`r`| Refresh list with a fetch and prune |
|`enter`| Select highlighted item |
|`space`| Git log |
|`q, C-c, esc`| Quit |

## Contributing
Please refer to the [Contributing Guidelines](./CONTRIBUTING.md)

## Contributors
Many thanks to all those who have helped!

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/29239201?v=4" width="80px;"/><br /><sub><b>Brandon Benefield</b></sub>](https://www.bbenefield.com)<br />[📖](https://github.com/jwu910/check-it-out/commits?author=bbenefield89 "Documentation") | [<img src="https://avatars1.githubusercontent.com/u/32409546?v=4" width="80px;"/><br /><sub><b>Aaron Casanova</b></sub>](https://github.com/casyjs)<br />[💻](https://github.com/jwu910/check-it-out/commits?author=casyjs "Code") | [<img src="https://avatars1.githubusercontent.com/u/6403097?v=4" width="80px;"/><br /><sub><b>Drew Brokke</b></sub>](https://github.com/drewbrokke)<br />[💻](https://github.com/jwu910/check-it-out/commits?author=drewbrokke "Code") [🤔](#ideas-drewbrokke "Ideas, Planning, & Feedback") | [<img src="https://avatars3.githubusercontent.com/u/35710155?v=4" width="80px;"/><br /><sub><b>Johanna Tchon</b></sub>](https://github.com/jotchon)<br />[💻](https://github.com/jwu910/check-it-out/commits?author=jotchon "Code") | [<img src="https://avatars1.githubusercontent.com/u/18720522?v=4" width="80px;"/><br /><sub><b>Jenell Pizarro</b></sub>](https://www.jenellpizarro.com/)<br />[📖](https://github.com/jwu910/check-it-out/commits?author=nellarro "Documentation") | [<img src="https://avatars2.githubusercontent.com/u/12107969?v=4" width="80px;"/><br /><sub><b>Joshua Wu</b></sub>](http://www.linkedin.com/in/wujoshua)<br />[🐛](https://github.com/jwu910/check-it-out/issues?q=author%3Ajwu910 "Bug reports") [💻](https://github.com/jwu910/check-it-out/commits?author=jwu910 "Code") [📖](https://github.com/jwu910/check-it-out/commits?author=jwu910 "Documentation") [🤔](#ideas-jwu910 "Ideas, Planning, & Feedback") [🚇](#infra-jwu910 "Infrastructure (Hosting, Build-Tools, etc)") [👀](#review-jwu910 "Reviewed Pull Requests") | [<img src="https://avatars2.githubusercontent.com/u/34019925?v=4" width="80px;"/><br /><sub><b>Rebecca Hong</b></sub>](http://www.linkedin.com/in/rehong)<br />[🎨](#design-rebeccahongsf "Design") |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [<img src="https://avatars3.githubusercontent.com/u/25625490?v=4" width="80px;"/><br /><sub><b>Jesse Ma</b></sub>](https://github.com/jma26)<br />[💻](https://github.com/jwu910/check-it-out/commits?author=jma26 "Code") | [<img src="https://avatars2.githubusercontent.com/u/16655146?v=4" width="80px;"/><br /><sub><b>Kien Do</b></sub>](https://github.com/kienD)<br />[💬](#question-kienD "Answering Questions") [🐛](https://github.com/jwu910/check-it-out/issues?q=author%3AkienD "Bug reports") [🤔](#ideas-kienD "Ideas, Planning, & Feedback") | [<img src="https://avatars2.githubusercontent.com/u/1088312?v=4" width="80px;"/><br /><sub><b>Vu Tran</b></sub>](http://twitter.com/tranvu)<br />[💬](#question-vutran "Answering Questions") [📖](https://github.com/jwu910/check-it-out/commits?author=vutran "Documentation") [🤔](#ideas-vutran "Ideas, Planning, & Feedback") [📢](#talk-vutran "Talks") |
<!-- ALL-CONTRIBUTORS-LIST:END -->

### License
MIT @ [Joshua Wu](https://www.npmjs.com/~jwu910)
