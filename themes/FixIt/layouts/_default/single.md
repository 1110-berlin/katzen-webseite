{{- $params := .Scratch.Get "params" -}}
{{- $author := .Scratch.Get "author" -}}

# {{ .Title }}

---

> {{ T "single.author"}}: {{ with $author.link }}[{{ $author.name }}]({{ . }}){{ else }}{{ $author.name }}{{ end }}  
> URL: {{ .Permalink }}  
> {{ if $params.repost.enable | and (hasPrefix $params.repost.url "http") }}> {{ T "single.repost" }} URL: {{ $params.repost.url }}{{ end }}
