# weechataboo
WeeChat + Weeaboo faces = *Weechataboo*

A [WeeChat](https://weechat.org/)-Script to replace emotion-tags with
random emoticon. Emotion tags in text are starting with `~~`. The text
`hello ~~hug` will be `hello (っ´▽｀)っ`. \
Oh. It's written in Scheme.

```
/help weechataboo

> [guile/weechataboo]  /weechataboo  
>
> This script automatically replaces written emotion-keywords
> with a random emoticon from a list of matching ones. The
> keyword must have two tildes (~~) as a prefix.
> Example: ~~wink
>
> All values are comma separated. Please make sure that every
> emotion in the `emotions`-list has its own entry!
>
> → Keywords: /set plugins.var.guile.weechataboo.emotions
> → Emoticons: /set plugins.var.guile.weechataboo.$EMOTION
```
