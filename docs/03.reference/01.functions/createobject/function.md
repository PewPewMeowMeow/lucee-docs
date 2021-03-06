---
title: CreateObject
id: function-createobject
related:
categories:
    - component
---

The CreateObject function takes different arguments depending on the value of the first argument:

```luceescript
CreateObject('com', class, context, serverName)
CreateObject('component', component-name)
CreateObject('corba', context, class, locale)
CreateObject('java', class)
CreateObject('webservice', urltowsdl, [, portname])
```

>>>> In Lucee 5, this function has been deprecated in favour of the `new object()` syntax (reference needed). In line with our [committment to CFML](http://lucee.org/blog/the-lucee-language.html), this function will never be dropped from the language and you are safe to use it going forward.
