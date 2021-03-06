# 1c-syntax
Syntax definition rules for 1C:Enterprise 8 for tmLanguage-based text editors (Sublime Text, Atom and VS Code).

## Цель репозитория
Данный репозиторий создан для консолидации работ по созданию пакетов для текстовых редакторов [Atom](https://atom.io/), [Sublime Text](http://www.sublimetext.com/) и [Visual Studio Code](https://www.visualstudio.com/en-us/products/code-vs.aspx).  
Под каждый из редакторов создан отдельный репозиторий и опубликован соответствующий пакет на площадке распространения пакетов:

| Репозиторий | Пакет |
|:---:|:---:|
| [Sublime Text](https://github.com/xDrivenDevelopment/sublime-language-1c-bsl) | [Package control](https://packagecontrol.io/packages/Language%201C%20(BSL)) |
| [Atom](https://github.com/xDrivenDevelopment/atom-language-1c-bsl) | [Atom.io/packages](https://atom.io/packages/language-1c-bsl) |
| [VS Code](https://github.com/xDrivenDevelopment/vsc-language-1c-bsl) | [Marketplace](https://marketplace.visualstudio.com/items/xDrivenDevelopment.language-1c-bsl) |

Разработка описания грамматики языка на основе [формата TextMate](http://manual.macromates.com/en/language_grammars) ведется в специальном [YAML-файле](https://github.com/xDrivenDevelopment/1c-syntax/blob/master/1c.YAML-tmLanguage), описание которого и примеры использования вы можете найти [здесь](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html).

## Дополнительные возможности

Помимо, собственно, грамматики, мы пытаемся добавить в редакторы дополнительные
возможности, которые могут упростить работу с 1С.  
На данный момент список таких фич выглядит вот так:

| Функционал \ Поддержка в редакторах | [Atom](https://github.com/xDrivenDevelopment/atom-language-1c-bsl) | [Sublime Text](https://github.com/xDrivenDevelopment/sublime-language-1c-bsl) | [VS Code](https://github.com/xDrivenDevelopment/vsc-language-1c-bsl) |
|---|:---:|:---:|:---:|
| Блочное комментирование через `//` | Есть | Есть | Есть |
| Список процедур и функций текущего файла | Есть | Есть | [Нет](https://github.com/xDrivenDevelopment/1c-syntax/issues/59) |
| Переход к опредлению процедур и функций | Есть | Есть | [Нет](https://github.com/xDrivenDevelopment/1c-syntax/issues/60) |
| Автоматическое добавление символа &#124; при добавлении новой строки во время редактирования строкового литерала | Есть | Есть | Есть |
| Запуск скриптов `.os`/`.bsl` с помощью OneScript | Есть | Есть | Есть |

Информацию об использовании каждой из возможностей вы найдете в README
соответствующего редактора.

## Сотрудничество

Если вы разработчик и хотите помочь с разработкой пакетов и/или грамматикой, пожалуйста, ознакомьтесь с [гайдом для разработчиков](https://github.com/xDrivenDevelopment/1c-syntax/blob/master/CONTRIBUTING.md).  
Уже поставленные задачи по разработке можно найти на странице [Issues](https://github.com/xDrivenDevelopment/1c-syntax/issues) данного репозитория.
