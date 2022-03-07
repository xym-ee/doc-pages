# 文档模板

<img alt="GitHub last commit" src="https://badgen.net/github/last-commit/0xyMeng/doc-pages">


部署于Github Pages，可以用来当个人网站或者说明文档。

<center>
    <a>
    @{{- author -}}
    </a>
    {{ __.revision | default: "Revision" }}
    <a class="text-gray" href="{{ docs.repository_url }}/commit/{{ docs.build_revision }}" title="{{ docs.build_revision }}" rel="noreferrer" target="_blank">
        {{- docs.build_revision | slice: 0, 7 -}}
    </a>
</center>


