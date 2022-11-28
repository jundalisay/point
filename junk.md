.win    186 260
.bid    186 260
.party  186 260
.top    156 261

.in 983 357
.work   160 364
.icu    88  364
.rodeo  313 364


http://dccp.ph/events
https://www.facebook.com/werise.community/
https://www.smxconventioncenter.com/smx-manila-calendar-of-events/

Alibaba
1. Ecommerce system
2. Payments  points
3. Logistics hub

Alibaba tested during 11/11


ganache chain
truffle cli 
metamask wallet


<section class="section container"> 
  <h2 class="subtitle is-3 has-text-centered pb-2 mt-5">Latest Government News</h2>        
  <div class="has-text-centered columns is-mobile is-multiline">
    {{ range first 3 (where .Site.RegularPages "Type" "government") }}
      <div class="column is-12-touch is-4-desktop">
        <a href="{{ .Permalink }}">
          <div class="card zoom">

            {{ with .Params.image }}
              <img src="{{ . | absURL }}" alt="{{ . }}" class="card-img-top">
            {{ end }}

            <h3 class="title is-4 mt-4 mx-4">{{ .Title }}</h3>
            <small class="mx-4 pb-4">{{ .Params.Description }}</small>
          </div>
        </a>
      </div>
    {{ end }}
  </div>
</section>



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

                                                                            

