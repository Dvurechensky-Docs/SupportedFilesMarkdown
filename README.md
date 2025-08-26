<p align="center">✨Dvurechensky✨</p>

<p align="center">
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=435&lines=%D0%9F%D0%BE%D0%B2%D1%82%D0%BE%D1%80%D0%B5%D0%BD%D0%B8%D0%B5+-+%D0%BC%D0%B0%D1%82%D1%8C+%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D1%8F" alt="Typing SVG" /></a>
</p>
<p align="center">
    <a href="https://sites.google.com/view/dvurechensky" target="_blank"><img alt="Static Badge" src="https://shields.dvurechensky.pro/badge/Dvurechensky-Nikolay-blue"></a>
</p>

# Поддерживаемые расширения файлов 🌊 в Markdown для Gitea | Github

- [Поддерживаемые расширения файлов 🌊 в Markdown для Gitea | Github](#поддерживаемые-расширения-файлов--в-markdown-для-gitea--github)
  - [Таблица сравнения 🌀](#таблица-сравнения-)
  - [mermaid ⛄](#mermaid-)
  - [geoJSON ⛄](#geojson-)
  - [topoJSON ⛄](#topojson-)
  - [STL ⛄](#stl-)
  - [Markdown ⛄](#markdown-)
  - [SVG ⛄](#svg-)
  - [PNG ⛄](#png-)
  - [GIF ⛄](#gif-)
  - [JPEG ⛄](#jpeg-)
  - [Text ⛄](#text-)

## Таблица сравнения 🌀

| Тип содержимого | Поддерживаемые расширения                                                        | Описание                                       | Github | Gitea |
| --------------- | -------------------------------------------------------------------------------- | ---------------------------------------------- | ------ | ----- |
| mermaid         | [.mermaid](./Files/pie_chart.mermaid), [.mmd](./Files/pie_chart.mmd)             | Инструмент для построения диаграмм и графиков  | ✅     | ✅    |
| geoJSON         | [.geojson](./Files/fictional_park.geojson), [.json](./Files/fictional_park.json) | Формат для кодирования географических данных   | ✅     | ❌    |
| topoJSON        | [.topojson](./Files/fictional_park.topojson), .json                              | Расширение GeoJSON для топологических данных   | ✅     | ❌    |
| STL             | [.stl](./Files/solid_cube.stl)                                                   | Формат файлов для 3D-моделей                   | ✅     | ❌    |
| Markdown        | [.markdown](./Files/documentation.markdown), [.md](./Files/documentation.md)     | Язык разметки для форматирования текста        | ✅     | ✅    |
| SVG             | [.svg](./Files/theultimatemarkdowncheatsheet-brightgreen.svg)                    | Формат файлов масштабируемой векторной графики | ✅     | ✅    |
| PNG             | [.png](./Files/BinaryTree.png)                                                   | Формат файлов портативной сетевой графики      | ✅     | ✅    |
| GIF             | [.gif](./Files/ruby.gif)                                                         | Формат обмена графическими файлами             | ✅     | ✅    |
| JPEG            | [.jpg](./Files/BinaryTree.jpg), .jpeg                                            | Формат файлов изображений JPEG                 | ✅     | ✅    |
| Text            | [.txt](./Files/todo.txt)                                                         | Обычный текстовый файл                         | ✅     | ✅    |

## mermaid ⛄

```mermaid
pie
"Movies" : 80
"TV shows" : 20
```

````md
```mermaid
pie
"Movies" : 80
"TV shows" : 20
```
````

## geoJSON ⛄

```geojson
{
	"type": "FeatureCollection",
	"features": [
		{
			"type": "Feature",
			"geometry": {
				"type": "Polygon",
				"coordinates": [
					[
						[
							-100,
							40
						],
						[
							-99,
							40
						],
						[
							-99,
							41
						],
						[
							-100,
							41
						],
						[
							-100,
							40
						]
					]
				]
			},
			"properties": {
				"name": "Fictional Park",
				"description": "A large, fictional park for demonstration purposes."
			}
		}
	]
}
```

````md
```geojson
{
	"type": "FeatureCollection",
	"features": [
		{
			"type": "Feature",
			"geometry": {
				"type": "Polygon",
				"coordinates": [
					[
						[
							-100,
							40
						],
						[
							-99,
							40
						],
						[
							-99,
							41
						],
						[
							-100,
							41
						],
						[
							-100,
							40
						]
					]
				]
			},
			"properties": {
				"name": "Fictional Park",
				"description": "A large, fictional park for demonstration purposes."
			}
		}
	]
}
```
````

## topoJSON ⛄

```topojson
{
	"type": "Topology",
	"objects": {
		"fictional_park": {
			"type": "GeometryCollection",
			"geometries": [
				{
					"type": "Polygon",
					"arcs": [
						[
							0
						]
					],
					"properties": {
						"name": "Fictional Park",
						"description": "A large, fictional park for demonstration purposes."
					}
				}
			]
		}
	},
	"arcs": [
		[
			[
				-100,
				40
			],
			[
				-99,
				40
			],
			[
				-99,
				41
			],
			[
				-100,
				41
			],
			[
				-100,
				40
			]
		]
	],
	"transform": {
		"scale": [
			0.0001,
			0.0001
		],
		"translate": [
			-100,
			40
		]
	}
}
```

````md
```topojson
{
	"type": "Topology",
	"objects": {
		"fictional_park": {
			"type": "GeometryCollection",
			"geometries": [
				{
					"type": "Polygon",
					"arcs": [
						[
							0
						]
					],
					"properties": {
						"name": "Fictional Park",
						"description": "A large, fictional park for demonstration purposes."
					}
				}
			]
		}
	},
	"arcs": [
		[
			[
				-100,
				40
			],
			[
				-99,
				40
			],
			[
				-99,
				41
			],
			[
				-100,
				41
			],
			[
				-100,
				40
			]
		]
	],
	"transform": {
		"scale": [
			0.0001,
			0.0001
		],
		"translate": [
			-100,
			40
		]
	}
}
```
````

## STL ⛄

```stl
solid cube
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 0 0
      vertex 1 1 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 1 0
      vertex 0 1 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 1
      vertex 1 0 1
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 1
      vertex 1 1 1
      vertex 0 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 1 0
      vertex 0 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 1 1
      vertex 0 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 1 0 0
      vertex 1 1 0
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 1 0 0
      vertex 1 1 1
      vertex 1 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 0 1
      vertex 1 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 0 1
      vertex 1 0 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 1 0
      vertex 0 1 1
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 1 0
      vertex 1 1 1
      vertex 1 1 0
    endloop
  endfacet
endsolid cube
```

````md
```stl
solid cube
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 0 0
      vertex 1 1 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 1 0
      vertex 0 1 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 1
      vertex 1 0 1
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 1
      vertex 1 1 1
      vertex 0 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 1 0
      vertex 0 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 1 1
      vertex 0 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 1 0 0
      vertex 1 1 0
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 1 0 0
      vertex 1 1 1
      vertex 1 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 0 0 1
      vertex 1 0 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 0 0
      vertex 1 0 1
      vertex 1 0 0
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 1 0
      vertex 0 1 1
      vertex 1 1 1
    endloop
  endfacet
  facet normal 0 0 0
    outer loop
      vertex 0 1 0
      vertex 1 1 1
      vertex 1 1 0
    endloop
  endfacet
endsolid cube
```
````

## Markdown ⛄

**It works.**

```md
**It works.**
```

## SVG ⛄

<img src="./Files/theultimatemarkdowncheatsheet-brightgreen.svg" alt="Зеленая кнопка с текстом 'theultimatemarkdowncheatsheet', написанным белыми буквами."/>

```md
<img src="./Files/theultimatemarkdowncheatsheet-brightgreen.svg" alt="Зеленая кнопка с текстом 'theultimatemarkdowncheatsheet', написанным белыми буквами."/>
```

## PNG ⛄

<img src="./Files/BinaryTree.png" alt="Logo of BinaryTree featuring a hexagonal icon."/>

```md
<img src="./Files/BinaryTree.png" alt="Logo of BinaryTree featuring a hexagonal icon."/>
```

## GIF ⛄

<img src="./Files/ruby.gif" alt="Экран терминала, отображающий интерактивную среду Ruby (irb)."/>

```md
<img src="./Files/ruby.gif" alt="Экран терминала, отображающий интерактивную среду Ruby (irb)."/>
```

## JPEG ⛄

<img src="./Files/BinaryTree.jpg" alt="Логотип BinaryTree, изображающий шестиугольный значок и текст «BINARY TREE», написанный заглавными буквами справа от значка.
"/>

```md
<img src="./Files/BinaryTree.jpg" alt="Логотип BinaryTree, изображающий шестиугольный значок и текст «BINARY TREE», написанный заглавными буквами справа от значка.
"/>
```

## Text ⛄

```txt
[x] Task 1
[] Task 2
```

````md
```txt
[x] Task 1
[] Task 2
```
````

<p align="center">✨Dvurechensky✨</p>
