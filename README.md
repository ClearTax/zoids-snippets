# zoids-snippets

Supercharge your react component development with zoids using zoids snippets

## "What is zoids?"

Zoids is the internal design system for cleartax built with react and styled-components.

## Zoids Snippets

|  Prefix   | Component                                           |
| ------:   | --------------------------------------------------- |
|  `zi→`    | `import { componentName } from '@cleartax/zoids'`   |
|  `zib→`   | `import { button } from '@cleartax/zoids'`          |
|  `zcon→`  | `<Container></Container>`                           |
|  `zcel→`  | `<Cell width=''></Cell>`                            |
|  `zcelc→` | `<Cell width='' className=''></Cell>`               |
|  `zcelc→` | `<Cell width='' className=''></Cell>`               |
|  `zsk→`   | `<Skeleton active title loading=''></Skeleton>`     |
|  `zhe→`   | `<Heading text='' size='' />`                       |
|  `zte→`   | `<Text></Text>`                                     |
|  `zbu→`   | `<Button nature='' size='' onClick=''></Button>`    |
|  `zbug→`  | `<ButtonGroup></ButtonGroup>`                       |
|  `zcard→` | `<Card nature=''></Card>`                           |
|  `zcardp→`| `<Card nature='' align='left'></Card>`              |
|  `zlo→`   | `<Loader nature=''></Loader>`                       |
|  `zme→`   | `<Message nature='' heading='' description='' />`   |
|  `zli→`   | `<List type='ul' size='' listStyle=''></List>`      |
|  `zpg→`   | `<Pagination total='' />`                           |
|  `zbr→`   | `<Breadcrumbs breadcrumbs={} inline={} />`          |
|  `ztag→`  | `<Tag color=''></Tag>`                              |
|  `zto→`   | `<Tooltip content='' placement=''></Tooltip>`       |
|  `zmod→`  | `<Modal size='m' open={}></Modal>`                  |
|  `zmodf→`  | `<Modal.Footer></Modal.Footer>`                    |

### See it in action

![pinchy](https://assets1.cleartax-cdn.com/cleargst-frontend/misc/1566637441_zoid-snippets.gif)

## Super snippet

Built a new Zoids component? Creating a snippet to support your component is super easy.

Use the `snip` snippet to create Zoids snippets

![snippet](https://assets1.cleartax-cdn.com/cleargst-frontend/misx/1566657235_zoids_snippet.gif)

## Guidelines to contribute

- Add your snippet to the `snippets/zoids.json` file.
- Update the [Zoids snippets](https://github.com/ClearTax/zoids-snippets#zoids-snippets-1) section in `README.md`.
- Update the `CHANGELOG.md`.
- Bump up the version in `package.json`.
- Install Visual Studio Code Extention by running `npm install -g vsce`.
- Run `vsce package` to build a new version.
- Go to cleartax's Visual Studio [marketplace](https://marketplace.visualstudio.com/manage/publishers/cleartax) and upload the package.

> Note: Reach out to `rajanand@cleartax.in` to get access to publish the package in marketplace
