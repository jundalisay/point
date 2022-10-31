The Point covers all important events that are relevabt for IT, startups, agriculture, business, food, health, education, etc.

March 4, 1918 Kansas - May
Sept Oct 1918 Phily Boston San Fransisco


AGRI
agri
food

BIZ
biz
retail
startups

COMMUNITY
culture
education
environment
tourism
welfare

TECH
compete
crypto
cyber
energy
science




OTHERS
govt
jobs
promos







{{ with .Param "design.colors.light" }}
$light: {{ . }};
{{ end }}
{{ with .Param "design.colors.dark" }}
$dark: {{ . }};
{{ end }}
{{ with .Param "design.colors.link" }}
$link: {{ . }};
{{ end }}
{{ with .Param "design.colors.success" }}
$success: {{ . }};
{{ end }}



<iframe width="560" height="315" src="https://www.youtube.com/embed/5fL2_ZcRgNQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


{{ template "_internal/opengraph.html" $page }}


{{ if $isAuthorEnabled }}
                                    {{ with $item.Params.author }}
                                        <div class="control">
                                            <div class="tags has-addons">
                                                <span class="tag is-primary"><i class="fas fa-user"></i></span>
                                                <span class="tag">{{ . }}</span>
                                            </div>
                                        </div>
                                    {{ end }}
                                {{ end }} 


                                            {{ if $isAuthorEnabled }}
                                                {{ with $item.Params.author }}
                                                    <div class="control">
                                                        <div class="tags has-addons">
                                                            <span class="tag is-primary"><i class="fas fa-user"></i></span>
                                                            <span class="tag">{{ . }}</span>
                                                        </div>
                                                    </div>
                                                {{ end }}
                                            {{ end }}

                                                                            

