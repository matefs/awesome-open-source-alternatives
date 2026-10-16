# Awesome Open-Source Alternatives [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

Curated open-source, self-hostable alternatives to popular paid apps and services.

> Inspired by [opensource.builders](https://opensource.builders/).

**Legend:** 🖥️ needs a GPU for good performance · ⚠️ see note

## Contents

- [AI Assistants and Coding](#ai-assistants-and-coding)
- [AI Audio and Voice](#ai-audio-and-voice)
- [AI Image and Design](#ai-image-and-design)
- [AI Video](#ai-video)
- [Language and Documents](#language-and-documents)
- [Learning](#learning)
- [Media and Entertainment](#media-and-entertainment)
- [Cloud Storage and Office](#cloud-storage-and-office)
- [Notes and Productivity](#notes-and-productivity)
- [Communication](#communication)
- [Security and Networking](#security-and-networking)
- [Developer Tools](#developer-tools)
- [Hosting and Infrastructure](#hosting-and-infrastructure)
- [Marketing and Analytics](#marketing-and-analytics)
- [Publishing and Social](#publishing-and-social)
- [Business](#business)
- [Personal and Home](#personal-and-home)
- [Contributing](#contributing)

---

## AI Assistants and Coding

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [ChatGPT Plus](https://chatgpt.com) / [Claude Pro](https://claude.ai) | [Ollama](https://github.com/ollama/ollama) + [Open WebUI](https://github.com/open-webui/open-webui) | 🖥️ Local models are below frontier quality |
| [Character.ai](https://character.ai) | [SillyTavern](https://github.com/SillyTavern/SillyTavern) | Needs a local or API LLM |
| [GitHub Copilot](https://github.com/features/copilot) / [Cursor](https://cursor.com) | [Continue](https://github.com/continuedev/continue), [Tabby](https://github.com/TabbyML/tabby) | 🖥️ Pair with a code model |
| [Lovable](https://lovable.dev) / [Bolt](https://bolt.new) / [v0](https://v0.dev) | [bolt.diy](https://github.com/stackblitz-labs/bolt.diy) | |
| [NotebookLM](https://notebooklm.google) | [Open Notebook](https://github.com/lfnovo/open-notebook), [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | AnythingLLM exposes a REST API for RAG |
| [Perplexity](https://perplexity.ai) | [Perplexica](https://github.com/ItzCrazyKns/Perplexica) + [SearXNG](https://github.com/searxng/searxng) | |
| [Gamma](https://gamma.app) | [Presenton](https://github.com/presenton/presenton) | |
| Hosted RAG / LLM app builders | [Dify](https://github.com/langgenius/dify) | |

## AI Audio and Voice

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Adobe Podcast Enhance](https://podcast.adobe.com/enhance) | [DeepFilterNet](https://github.com/Rikorose/DeepFilterNet), [Resemble Enhance](https://github.com/resemble-ai/resemble-enhance) | |
| [ElevenLabs](https://elevenlabs.io) (TTS, voice cloning) | [XTTS](https://github.com/idiap/coqui-ai-TTS), [F5-TTS](https://github.com/SWivid/F5-TTS) | 🖥️ |
| [ElevenLabs Voice Changer](https://elevenlabs.io/voice-changer) / [Voice.ai](https://voice.ai) | [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI), [Applio](https://github.com/IAHispano/Applio) | 🖥️ |
| [ElevenLabs Dubbing](https://elevenlabs.io/dubbing) / [HeyGen Translate](https://heygen.com) | [pyVideoTrans](https://github.com/jianchang512/pyvideotrans) | |
| [Speechify](https://speechify.com) | [Kokoro](https://github.com/hexgrad/kokoro), [Piper](https://github.com/rhasspy/piper) | Piper runs fine on CPU |
| [Otter.ai](https://otter.ai) | [WhisperX](https://github.com/m-bain/whisperX), [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | WhisperX adds speaker diarization |
| [Lalal.ai](https://lalal.ai) | [Demucs](https://github.com/facebookresearch/demucs), [Ultimate Vocal Remover](https://github.com/Anjok07/ultimatevocalremovergui) | |
| [Suno](https://suno.com) | [ACE-Step](https://github.com/ace-step/ACE-Step), [YuE](https://github.com/multimodal-art-projection/YuE) | 🖥️ ⚠️ Quality well below Suno |

## AI Image and Design

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Adobe Photoshop](https://adobe.com/photoshop) | [PhotoCraft](https://github.com/storytold/photocraft), [GIMP](https://gitlab.gnome.org/GNOME/gimp), [Krita](https://invent.kde.org/graphics/krita) | ⚠️ PhotoCraft is in early alpha; opens and saves PSD |
| [Adobe Illustrator](https://adobe.com/illustrator) | [VectorCraft](https://github.com/storytold/vectorcraft), [Inkscape](https://gitlab.com/inkscape/inkscape) | ⚠️ VectorCraft is in early alpha |
| [Adobe Lightroom](https://adobe.com/lightroom) | [LightCraft](https://github.com/storytold/lightcraft), [darktable](https://github.com/darktable-org/darktable), [RawTherapee](https://github.com/Beep6581/RawTherapee) | ⚠️ LightCraft is in early alpha |
| [Adobe InDesign](https://adobe.com/indesign) | [DesignCraft](https://github.com/storytold/designcraft), [Scribus](https://github.com/scribusproject/scribus) | ⚠️ DesignCraft is in early alpha |
| Photoshop Generative Fill | [Krita AI Diffusion](https://github.com/Acly/krita-ai-diffusion), [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 🖥️ |
| [Midjourney](https://midjourney.com) / [DALL·E](https://openai.com/dall-e) | [ComfyUI](https://github.com/comfyanonymous/ComfyUI) (Flux, SDXL), [ArtCraft](https://github.com/storytold/artcraft) | 🖥️ ⚠️ ArtCraft has no clearly stated license; hosted generation uses paid credits |
| [Cleanup.pictures](https://cleanup.pictures) | [IOPaint](https://github.com/Sanster/IOPaint) | |
| [Remove.bg](https://remove.bg) | [rembg](https://github.com/danielgatis/rembg) | |
| [Topaz Photo AI](https://topazlabs.com) | [Upscayl](https://github.com/upscayl/upscayl), [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) | |
| [Meshy](https://meshy.ai) (text/image to 3D) | [TRELLIS](https://github.com/microsoft/TRELLIS), [Hunyuan3D](https://github.com/Tencent/Hunyuan3D-2) | 🖥️ |
| [Figma](https://figma.com) | [Penpot](https://github.com/penpot/penpot) | |
| [Canva](https://canva.com) | [Penpot](https://github.com/penpot/penpot) | ⚠️ Partial replacement |

## AI Video

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Adobe Premiere Pro](https://adobe.com/premiere) | [FilmCraft](https://github.com/storytold/filmcraft), [Kdenlive](https://invent.kde.org/multimedia/kdenlive), [Shotcut](https://github.com/mltframework/shotcut) | ⚠️ FilmCraft is in early alpha; can't open .prproj |
| [Adobe After Effects](https://adobe.com/aftereffects) | [EffectCraft](https://github.com/storytold/effectcraft), [Natron](https://github.com/NatronGitHub/Natron) | ⚠️ EffectCraft is in early alpha |
| [Runway](https://runwayml.com) / [Kling](https://klingai.com) | [Wan](https://github.com/Wan-Video/Wan2.1), [HunyuanVideo](https://github.com/Tencent/HunyuanVideo), [LTX-Video](https://github.com/Lightricks/LTX-Video) | 🖥️ High VRAM |
| [HeyGen](https://heygen.com) / [D-ID](https://d-id.com) | [LivePortrait](https://github.com/KwaiVGI/LivePortrait), [MuseTalk](https://github.com/TMElyralab/MuseTalk) | 🖥️ |
| [Opus Clip](https://opus.pro) | [FunClip](https://github.com/modelscope/FunClip), [ClipsAI](https://github.com/ClipsAI/clipsai), [AI-Youtube-Shorts-Generator](https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator) | |
| [Submagic](https://submagic.co) | [WhisperX](https://github.com/m-bain/whisperX) + [FFmpeg](https://github.com/FFmpeg/FFmpeg) | DIY pipeline |
| [Descript](https://descript.com) (silence removal) | [auto-editor](https://github.com/WyattBlue/auto-editor) | |

## Language and Documents

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [DeepL](https://deepl.com) | [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) | A local LLM also works well |
| [Grammarly](https://grammarly.com) | [LanguageTool](https://github.com/languagetool-org/languagetool) | |
| [Mathpix](https://mathpix.com) / PDF OCR | [Marker](https://github.com/VikParuchuri/marker), [MinerU](https://github.com/opendatalab/MinerU), [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) | |
| [Adobe Acrobat](https://adobe.com/acrobat) | [PrintCraft](https://github.com/storytold/printcraft), [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF), [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) | |

## Learning

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Codecademy](https://codecademy.com) / [LeetCode](https://leetcode.com) | LLM + [Judge0](https://github.com/judge0/judge0) | ⚠️ Judge0 needs cgroups v1 |
| [Quizlet](https://quizlet.com) / [Duolingo](https://duolingo.com) | [Anki](https://github.com/ankitects/anki), [Revu](https://github.com/JuliusBrussee/revu-swift) | Pair Anki with an LLM to generate cards |

## Media and Entertainment

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Netflix](https://netflix.com) | [Jellyfin](https://github.com/jellyfin/jellyfin) | For your own media library |
| [Spotify](https://spotify.com) | [Navidrome](https://github.com/navidrome/navidrome), [Jellyfin](https://github.com/jellyfin/jellyfin) | For your own music library |
| [Audible](https://audible.com) | [Audiobookshelf](https://github.com/advplyr/audiobookshelf) | |
| [Kindle Unlimited](https://amazon.com/kindle-dbs/hz/subscribe/ku) | [Kavita](https://github.com/Kareadita/Kavita), [Calibre-Web](https://github.com/janeczku/calibre-web) | |
| [YouTube](https://youtube.com) | [PeerTube](https://github.com/Chocobozzz/PeerTube) | |
| [Twitch](https://twitch.tv) | [Owncast](https://github.com/owncast/owncast) | |

## Cloud Storage and Office

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Google Drive](https://drive.google.com) / [Dropbox](https://dropbox.com) | [Nextcloud](https://github.com/nextcloud/server), [Seafile](https://github.com/haiwen/seafile), [ownCloud](https://github.com/owncloud/core), [Syncthing](https://github.com/syncthing/syncthing) | |
| [Google Photos](https://photos.google.com) / iCloud Photos | [Immich](https://github.com/immich-app/immich), [PhotoPrism](https://github.com/photoprism/photoprism), [LibrePhotos](https://github.com/LibrePhotos/librephotos) | |
| [Google Docs](https://docs.google.com) / [Microsoft 365](https://microsoft365.com) | [ONLYOFFICE](https://github.com/ONLYOFFICE/DocumentServer), [Collabora Online](https://github.com/CollaboraOnline/online), [CryptPad](https://github.com/cryptpad/cryptpad), [HedgeDoc](https://github.com/hedgedoc/hedgedoc) | |
| [Google Calendar](https://calendar.google.com) | [Radicale](https://github.com/Kozea/Radicale) | CalDAV/CardDAV server |
| Google Maps Timeline | [Dawarich](https://github.com/Freika/dawarich) | |
| Document scanning and archiving | [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | Strong built-in OCR |

## Notes and Productivity

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Evernote](https://evernote.com) | [Joplin](https://github.com/laurent22/joplin), [Trilium](https://github.com/TriliumNext/Trilium) | Joplin has OCR for attachments; Trilium does not |
| [Notion](https://notion.so) | [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy), [AFFiNE](https://github.com/toeverything/AFFiNE), [Outline](https://github.com/outline/outline) | |
| [Todoist](https://todoist.com) | [Vikunja](https://github.com/go-vikunja/vikunja) | |
| [Trello](https://trello.com) | [Planka](https://github.com/plankanban/planka), [Wekan](https://github.com/wekan/wekan), [Kanboard](https://github.com/kanboard/kanboard), [Taiga](https://github.com/taigaio) | |
| [Asana](https://asana.com) | [Leantime](https://github.com/Leantime/leantime) | |
| [Pocket](https://getpocket.com) / [Instapaper](https://instapaper.com) | [Wallabag](https://github.com/wallabag/wallabag), [Readeck](https://codeberg.org/readeck/readeck) | |
| [Feedly](https://feedly.com) | [FreshRSS](https://github.com/FreshRSS/FreshRSS), [Miniflux](https://github.com/miniflux/v2) | |
| [Calendly](https://calendly.com) | [Cal.com](https://github.com/calcom/cal.com) | |

## Communication

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Slack](https://slack.com) / [Discord](https://discord.com) | [Mattermost](https://github.com/mattermost/mattermost), [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat), [Zulip](https://github.com/zulip/zulip), [Element](https://github.com/element-hq/element-web), [Wire](https://github.com/wireapp), [Mezon](https://github.com/mezonai/mezon) | |
| [Zoom](https://zoom.com) / [Google Meet](https://meet.google.com) | [Jitsi Meet](https://github.com/jitsi/jitsi-meet) | |
| [Disqus](https://disqus.com) | [Isso](https://github.com/isso-comments/isso), [Remark42](https://github.com/umputun/remark42) | |

## Security and Networking

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [1Password](https://1password.com) / [LastPass](https://lastpass.com) | [Vaultwarden](https://github.com/dani-garcia/vaultwarden), [Bitwarden](https://github.com/bitwarden/server), [KeePassXC](https://github.com/keepassxreboot/keepassxc), [Buttercup](https://github.com/buttercup/buttercup-desktop), [Padloc](https://github.com/padloc/padloc), [Passwordcockpit](https://github.com/passwordcockpit) | |
| [Auth0](https://auth0.com) / [AWS Cognito](https://aws.amazon.com/cognito) | [Keycloak](https://github.com/keycloak/keycloak), [Authentik](https://github.com/goauthentik/authentik), [Authgear](https://github.com/authgear/authgear-server) | |
| [HashiCorp Vault](https://vaultproject.io) Enterprise | [OpenBao](https://github.com/openbao/openbao) | |
| [NextDNS](https://nextdns.io) | [Pi-hole](https://github.com/pi-hole/pi-hole), [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) | |
| [Tailscale](https://tailscale.com) | [Headscale](https://github.com/juanfont/headscale), [WireGuard](https://www.wireguard.com) | |
| [TeamViewer](https://teamviewer.com) | [RustDesk](https://github.com/rustdesk/rustdesk), [MeshCentral](https://github.com/Ylianst/MeshCentral), [Apache Guacamole](https://github.com/apache/guacamole-server), [Myrtille](https://github.com/cedrozor/myrtille) | |

## Developer Tools

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [GitHub](https://github.com) | [Gitea](https://github.com/go-gitea/gitea), [Forgejo](https://codeberg.org/forgejo/forgejo), [GitLab CE](https://gitlab.com/gitlab-org/gitlab), [Gogs](https://github.com/gogs/gogs), [OneDev](https://github.com/theonedev/onedev), [Pagure](https://pagure.io/pagure) | |
| [GitHub Actions](https://github.com/features/actions) | [Woodpecker CI](https://github.com/woodpecker-ci/woodpecker), [Jenkins](https://github.com/jenkinsci/jenkins), [act](https://github.com/nektos/act) | act runs Actions locally |
| [Jira](https://atlassian.com/software/jira) | [Plane](https://github.com/makeplane/plane), [OpenProject](https://github.com/opf/openproject), [Redmine](https://github.com/redmine/redmine) | |
| [TestRail](https://testrail.com) | [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) | |
| [Postman](https://postman.com) | [Bruno](https://github.com/usebruno/bruno), [Hoppscotch](https://github.com/hoppscotch/hoppscotch), [Voiden](https://github.com/VoidenHQ/voiden) | |
| [npm](https://npmjs.com) private registry | [Verdaccio](https://github.com/verdaccio/verdaccio), [Nexus](https://github.com/sonatype/nexus-public) | |
| [Docker Hub](https://hub.docker.com) | [Harbor](https://github.com/goharbor/harbor) | |
| [SonarCloud](https://sonarcloud.io) | [SonarQube Community](https://github.com/SonarSource/sonarqube) | |
| [Sentry](https://sentry.io) (SaaS) | [GlitchTip](https://gitlab.com/glitchtip), [Sentry self-hosted](https://github.com/getsentry/self-hosted) | |
| [Datadog](https://datadoghq.com) / [New Relic](https://newrelic.com) | [Grafana](https://github.com/grafana/grafana) + [Prometheus](https://github.com/prometheus/prometheus), [SigNoz](https://github.com/SigNoz/signoz) | |
| [UptimeRobot](https://uptimerobot.com) | [Uptime Kuma](https://github.com/louislam/uptime-kuma) | |
| [Mailtrap](https://mailtrap.io) | [Mailpit](https://github.com/axllent/mailpit) | Email testing |

## Hosting and Infrastructure

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Heroku](https://heroku.com) / [Vercel](https://vercel.com) / [Netlify](https://netlify.com) | [Coolify](https://github.com/coollabsio/coolify), [Dokku](https://github.com/dokku/dokku), [CapRover](https://github.com/caprover/caprover), [Tsuru](https://github.com/tsuru/tsuru), [OpenFaaS](https://github.com/openfaas/faas) | |
| [cPanel](https://cpanel.net) | [HestiaCP](https://github.com/hestiacp/hestiacp), [Webmin](https://github.com/webmin/webmin) | |
| [Amazon S3](https://aws.amazon.com/s3) | [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage), [SeaweedFS](https://github.com/seaweedfs/seaweedfs), [Ceph](https://github.com/ceph/ceph), [OpenStack Swift](https://github.com/openstack/swift), [MinIO](https://github.com/minio/minio) | ⚠️ MinIO restricted its community edition in 2025 |
| [Algolia](https://algolia.com) | [Meilisearch](https://github.com/meilisearch/meilisearch), [Typesense](https://github.com/typesense/typesense), [OpenSearch](https://github.com/opensearch-project/OpenSearch), [Elasticsearch](https://github.com/elastic/elasticsearch), [Sonic](https://github.com/valeriansaliou/sonic) | |
| [Firebase](https://firebase.google.com) | [Supabase](https://github.com/supabase/supabase), [Appwrite](https://github.com/appwrite/appwrite), [PocketBase](https://github.com/pocketbase/pocketbase) | |

## Marketing and Analytics

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Google Analytics](https://analytics.google.com) | [Plausible](https://github.com/plausible/analytics), [Umami](https://github.com/umami-software/umami), [Matomo](https://github.com/matomo-org/matomo), [Countly](https://github.com/Countly/countly-server), [Ackee](https://github.com/electerious/Ackee) | |
| [Hotjar](https://hotjar.com) / [Mixpanel](https://mixpanel.com) | [PostHog](https://github.com/PostHog/posthog) | |
| [Segment](https://segment.com) | [RudderStack](https://github.com/rudderlabs/rudder-server) | |
| [Mailchimp](https://mailchimp.com) | [Listmonk](https://github.com/knadh/listmonk) | |
| [Typeform](https://typeform.com) | [Formbricks](https://github.com/formbricks/formbricks), [OhMyForm](https://github.com/ohmyform/ohmyform) | |
| [SurveyMonkey](https://surveymonkey.com) | [LimeSurvey](https://github.com/LimeSurvey/LimeSurvey) | |
| [Zapier](https://zapier.com) / [Make](https://make.com) | [n8n](https://github.com/n8n-io/n8n), [Activepieces](https://github.com/activepieces/activepieces), [Huginn](https://github.com/huginn/huginn) | n8n uses a fair-code license |
| [Bitly](https://bitly.com) | [Shlink](https://github.com/shlinkio/shlink), [YOURLS](https://github.com/YOURLS/YOURLS) | |
| [Linktree](https://linktr.ee) | [LinkStack](https://github.com/LinkStackOrg/LinkStack) | |
| [Canny](https://canny.io) | [Fider](https://github.com/getfider/fider), [Astuto](https://github.com/riggraz/astuto) | |

## Publishing and Social

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [WordPress.com](https://wordpress.com) / [Wix](https://wix.com) | [WordPress](https://github.com/WordPress/WordPress), [Ghost](https://github.com/TryGhost/Ghost) | |
| [Medium](https://medium.com) / [Substack](https://substack.com) | [Ghost](https://github.com/TryGhost/Ghost), [WriteFreely](https://github.com/writefreely/writefreely) | |
| [Facebook](https://facebook.com) / [X](https://x.com) | [Mastodon](https://github.com/mastodon/mastodon) | |
| [Instagram](https://instagram.com) | [Pixelfed](https://github.com/pixelfed/pixelfed) | |

## Business

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [Salesforce](https://salesforce.com) / [HubSpot](https://hubspot.com) | [Twenty](https://github.com/twentyhq/twenty), [Odoo](https://github.com/odoo/odoo), [SuiteCRM](https://github.com/salesagility/SuiteCRM), [Erxes](https://github.com/erxes/erxes), [Customermates](https://github.com/customermates/customermates), [Corteza](https://github.com/cortezaproject), [IDURAR](https://github.com/idurar/idurar-erp-crm) | |
| [SAP](https://sap.com) | [ERPNext](https://github.com/frappe/erpnext), [Odoo](https://github.com/odoo/odoo) | |
| [Intercom](https://intercom.com) | [Chatwoot](https://github.com/chatwoot/chatwoot), [Chaskiq](https://github.com/chaskiq/chaskiq) | |
| [Zendesk](https://zendesk.com) | [Zammad](https://github.com/zammad/zammad), [FreeScout](https://github.com/freescout-help-desk/freescout), [osTicket](https://github.com/osTicket/osTicket), [UVDesk](https://github.com/uvdesk), [Znuny](https://github.com/znuny/Znuny), [OpenSupports](https://github.com/opensupports), [Faveo](https://github.com/ladybirdweb/faveo-helpdesk) | Znuny is the maintained fork of OTRS Community |
| [Shopify](https://shopify.com) | [WooCommerce](https://github.com/woocommerce/woocommerce), [Saleor](https://github.com/saleor/saleor), [Medusa](https://github.com/medusajs/medusa), [Sylius](https://github.com/Sylius/Sylius), [PrestaShop](https://github.com/PrestaShop/PrestaShop), [Bagisto](https://github.com/bagisto/bagisto), [Shopaholic](https://github.com/oc-shopaholic) | |
| [Apollo.io](https://apollo.io) / [Outreach](https://outreach.io) | [Overloop CLI](https://github.com/sortlist/overloop-cli) | |
| [Bombora](https://bombora.com) / [6sense](https://6sense.com) | [Signals CLI](https://github.com/sortlist/signals-cli) | |
| [GrantHub](https://granthub.com) | [GrantFlow](https://github.com/WabiSabikk/grantflow) | GrantHub is shutting down |

## Personal and Home

| Paid | Open-source alternatives | Notes |
|---|---|---|
| [YNAB](https://ynab.com) / [Mobills](https://mobills.com.br) | [Actual Budget](https://github.com/actualbudget/actual), [Firefly III](https://github.com/firefly-iii/firefly-iii) | |
| [Splitwise](https://splitwise.com) | [Spliit](https://github.com/spliit-app/spliit) | |
| [MyFitnessPal](https://myfitnesspal.com) / [Hevy](https://hevyapp.com) | [wger](https://github.com/wger-project/wger) | |
| Recipe apps | [Mealie](https://github.com/mealie-recipes/mealie), [Tandoor](https://github.com/TandoorRecipes/recipes) | |
| [Alexa](https://alexa.amazon.com) / [Google Home](https://home.google.com) | [Home Assistant](https://github.com/home-assistant/core) | |
| [Ring](https://ring.com) / cloud camera plans | [Frigate](https://github.com/blakeblackshear/frigate) | |

---

## Contributing

1. Add the alternative to the right category table, keeping rows alphabetical by paid app.
2. Link to the project's source repository, not its marketing site.
3. Only list projects that are open source and actively maintained.
4. Use the **Notes** column for license caveats, hardware needs or limitations.
