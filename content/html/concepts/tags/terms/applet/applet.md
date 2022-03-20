---
Title: '<applet>'
Description: 'Depreciated tag that was used to embed Java applets in HTML documents. It is no longer supported.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Tags'
  - 'Obsolete'
CatalogContent:
  - 'learn-html'
  - 'learn-java'
  - 'paths/front-end-engineer-career-path'
---

The `<applet>` tag was used to embed Java applets into an HTML page. It has been depreciated and removed from the [HTML specification](https://html.spec.whatwg.org/) and should no longer be used. Most browsers no longer support this tag.

The `<applet>` element included zero or more [`<param>`](https://www.codecademy.com/resources/docs/html/tags/param) elements to pass parameters on to the Java applet. The `<applet>` functionality is now incorporated into the [`<object>`](https://www.codecademy.com/resources/docs/html/tags/object) tag.

## Syntax

```html
<!-- This is no longer supported -->
<applet code="url of Java class file">
  Text displayed when no Java runtime is available.
</applet>
```

With parameter:

```html
<!-- This is no longer supported -->
<applet code="url of Java class file">
  <param name="name of parameter" value="value of parameter" />
  Text displayed when no Java runtime is available.
</applet>
```