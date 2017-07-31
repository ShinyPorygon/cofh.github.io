---
title: Downloads
layout: simple_info
redirect_from: /downloads.html
---

This page lists download links for all Team CoFH mods. For modpack permissions,
see [Permissions](/permissions/).

Before installing a mod, *always back up your world!* Especially when
it's a development build.

Report bugs and suggest new things
[here](https://github.com/CoFH/Feedback){:target="_blank"}.

<ul markdown="0" class="uk-grid uk-grid-width-large-1-2" data-uk-grid-margin data-uk-grid-match="{target: '.uk-panel'}">
    {% for mod in site.data.download-links %}
        <li id="{{mod.tag}}">
            <div class="uk-panel uk-panel-box">
                {% if mod.logo %}
                    <div class="cofh-download-logo" style="background-image: url(/assets/images/{{ mod.logo }})" title="{{mod.name}}"></div>
                {% else %}
                    <h3>{{mod.name}}</h3>
                {% endif %}

                <h4><strong>Requirements:</strong></h4>
                <ul>
                    {% for req in mod.requirements %}
                        <li><a href="{{req.link}}" {% if req.external %}target="_blank"{% endif %}>{{ req.name }}</a></li>
                    {% endfor %}
                </ul>

                {% if mod.note %}
                    <p>{{ mod.note }}</p>
                {% endif %}

                <div class="uk-button-group uk-margin-top">
                    <a class="uk-button uk-button-small uk-button-success uk-text-bold" href="{{mod.links.curse}}" target="_blank">Download on Curse</a>
                    <a class="uk-button uk-button-small" href="{{mod.links.curseforge}}" target="_blank">CurseForge</a>

                    {% if mod.links.changelog %}
                        <a class="uk-button uk-button-small" href="{{mod.links.changelog}}" target="_blank">Changelog</a>
                    {% endif %}
                </div>
            </div>
        </li>
    {% endfor %}
</ul>