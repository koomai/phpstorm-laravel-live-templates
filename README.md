### :warning: `This repository is no longer maintained.`

I no longer use this repository and do not maintain it anymore. 

My recommendation is to use [Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper), which is a much more robust solution for autocompletion and static checking.

## Laravel Live Templates for PhpStorm ##

How to:

1) Go to *Preferences | Tools | Settings Repository*

2) Add Read-only Source https://github.com/koomai/phpstorm-laravel-live-templates

3) Restart PhpStorm.

4) To see all templates, go to *Preferences | Live Templates* and expand the Template Group.


It's hard to remember shortcuts when there are a large number of options. A
more efficient way is to take advantage of PhpStorm's *Insert Live Template*
shortcut. Type as few or as many letters as you want and press `Cmd + J`. Then
continue typing to filter the options.

For example, for the Schema Builder, type `Sc` or `Sch` or `Schema` and press `Cmd + J`. 

**Note:** In the preview version of PhpStorm 8, live templates show up
automatically as you type the first few letters. You should still press `Cmd +
J` to filter out everything else (classes, variables, etc).

## Supported Live Templates ##

- [Annotations](#annotations)
- [Blade](#blade)
- [Input](#requests--input)
- [Request](#requests--input)
- [Cookie](#requests--input)
- [Route](#routes)
- [View](#views-responses-and-redirects)
- [Response](#views-responses-and-redirects)
- [Redirect](#views-responses-and-redirects)
- [Schema](#schema-builder) (includes column types)
- [Cache](#cache)
- [Form](#form)
- [Session](#session)
- [Helpers](#helpers)

### Annotations ###

![Route Annotations Screenshot](https://raw.githubusercontent.com/koomai/phpstorm-laravel-live-templates/develop/images/annotations.png)

Tip: Type `@` and then `Cmd+J` inside a docblock to see the options.

### Blade ###

![Laravel Blade Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/laravel-blade-screenshot.png)

### Requests & Input ###
![Laravel Input Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/input-demo.png)

![Laravel Input Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/input-file-demo.png)

![Laravel Requests Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/request-demo.png)

![Laravel Cookie Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/cookie-demo.png)

### Routes ###

![Laravel Routes Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/routes-demo.png)

All Route verbs are labelled `get` by default, but you can change it easily once the shortcut is expanded:

![Laravel Routes Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/routes-enum-demo.png)

### Views, Responses and Redirects ###

![Laravel Views Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/view-demo.png)

![Laravel Responses Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/response-demo.png)

![Laravel Redirects Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/redirect-demo.png)

### Schema Builder ###

![Laravel Schema Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/schema-demo.png)

![Laravel Tables Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/table-demo.png)

### Cache ###

![Laravel Cache Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/cache-demo.png)

### Form ###

![Laravel Form Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/form-demo.png)

### Session ###

![Laravel Session Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/session-demo.png)

### Helpers ###

![Laravel Helpers Screenshot](https://raw.github.com/koomai/phpstorm-laravel-live-templates/master/images/helpers-demo.png)

==========
#### Other goodies ####
Take your PhpStorm productivity to the next level with these [keyboard shortcuts](https://gist.github.com/koomai/9340189).
