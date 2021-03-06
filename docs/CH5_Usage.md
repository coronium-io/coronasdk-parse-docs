# Upload Content-Types

Parse requires the `content-type` header to be set on an upload. The plugin will try to "guess" the content type based on the file extension, so make sure to include it:

!!! info "Example"
  parse.upload( "myfilename.__png__" )

There is no guarantee that Parse uploads support all of the available types that the plugin can recognize.

*You can learn more about [file uploads](API_Files) in the API section*

## Recognized Extensions

Extension|Content-Type
---------|------------
dll|'application/x-msdownload'
qt|'video/quicktime'
log|'text/plain'
ico|'image/x-icon'
mp4a|'audio/mp4'
fhc|'image/x-freehand'
jpeg|'image/jpeg'
ma|'application/mathematica'
doc|'application/msword'
mesh|'model/mesh'
avi|'video/x-msvideo'
wmx|'video/x-ms-wmx'
wmv|'video/x-ms-wmv'
kmz|'application/vnd.google-earth.kmz'
caf|'audio/x-caf'
mp4|'video/mp4'
wm|'video/x-ms-wm'
ai|'application/postscript'
vob|'video/x-ms-vob'
asx|'video/x-ms-asf'
asf|'video/x-ms-asf'
mng|'video/x-mng'
mks|'video/x-matroska'
vcard|'text/vcard'
sgml|'text/sgml'
mkv|'video/x-matroska'
xhtml|'application/xhtml+xml'
m4v|'video/x-m4v'
xml|'application/xml'
webm|'video/webm'
rm|'application/vnd.rn-realmedia'
dvi|'application/x-dvi'
3gp|'video/3gpp'
mpeg|'video/mpeg'
mov|'video/quicktime'
ogv|'video/ogg'
m2v|'video/mpeg'
mpe|'video/mpeg'
x3dz|'model/x3d+xml'
mpg|'video/mpeg'
mpg4|'video/mp4'
mp4v|'video/mp4'
nsf|'application/vnd.lotus-notes'
psd|'image/vnd.adobe.photoshop'
nzb|'application/x-nzb'
torrent|'application/x-bittorrent'
jpgv|'video/jpeg'
h264|'video/h264'
h263|'video/h263'
h261|'video/h261'
3g2|'video/3gpp2'
rtx|'text/richtext'
vcf|'text/x-vcard'
pic|'image/x-pict'
rtf|'application/rtf'
ttf|'application/x-font-ttf'
mk3d|'video/x-matroska'
jpg|'image/jpeg'
3dml|'text/vnd.in3d.3dml'
ogx|'application/ogg'
png|'image/png'
list|'text/plain'
jpe|'image/jpeg'
dtd|'application/xml-dtd'
bz|'application/x-bzip'
crt|'application/x-x509-ca-cert'
sgm|'text/sgml'
asm|'text/x-asm'
wav|'audio/x-wav'
x3dvz|'model/x3d+vrml'
xsl|'application/xml'
wma|'audio/x-ms-wma'
text|'text/plain'
htm|'text/html'
html|'text/html'
csv|'text/csv'
css|'text/css'
pbm|'image/x-portable-bitmap'
ics|'text/calendar'
x3dv|'model/x3d+vrml'
vrml|'model/vrml'
xbm|'image/x-xbitmap'
gdl|'model/vnd.gdl'
xlt|'application/vnd.ms-excel'
tga|'image/x-tga'
rss|'application/rss+xml'
pct|'image/x-pict'
pcx|'image/x-pcx'
mp3|'audio/mpeg'
3ds|'image/x-3ds'
wax|'audio/x-ms-wax'
weba|'audio/webm'
svg|'image/svg+xml'
zip|'application/zip'
gif|'image/gif'
bmp|'image/bmp'
eps|'application/postscript'
swf|'application/x-shockwave-flash'
qxd|'application/vnd.quark.quarkxpress'
flac|'audio/x-flac'
aifc|'audio/x-aiff'
aif|'audio/x-aiff'
mp2|'audio/mpeg'
sgi|'image/sgi'
smil|'application/smil+xml'
s3m|'audio/s3m'
ogg|'audio/ogg'
atom|'application/atom+xml'
oga|'audio/ogg'
m2a|'audio/mpeg'
mp2a|'audio/mpeg'
aac|'audio/x-aac'
mpga|'audio/mpeg'
rmi|'audio/midi'
kar|'audio/midi'
midi|'audio/midi'
mid|'audio/midi'
tiff|'image/tiff'
xslt|'application/xslt+xml'
flv|'video/x-flv'
ra|'audio/x-pn-realaudio'
sql|'application/x-sql'
vcs|'text/x-vcalendar'
pgp|'application/pgp-encrypted'
mjp2|'video/mj2'
tar|'application/x-tar'
mp4s|'application/mp4'
sh|'application/x-sh'
bin|'application/octet-stream'
m3u|'audio/x-mpegurl'
msi|'application/x-msdownload'
mobi|'application/x-mobipocket-ebook'
lzh|'application/x-lzh-compressed'
iso|'application/x-iso9660-image'
woff|'application/font-woff'
xla|'application/vnd.ms-excel'
msh|'model/mesh'
epub|'application/epub+zip'
dmg|'application/x-apple-diskimage'
bz2|'application/x-bzip2'
txt|'text/plain'
json|'application/json'
7z|'application/x-7z-compressed'
rar|'application/x-rar-compressed'
tif|'image/tiff'
pdf|'application/pdf'
apk|'application/vnd.android.package-archive'
nfo|'text/x-nfo'
snd|'audio/basic'
xls|'application/vnd.ms-excel'
x3d|'model/x3d+xml'
aiff|'audio/x-aiff'
js|'application/javascript'
eot|'application/vnd.ms-fontobject'
ppt|'application/vnd.ms-powerpoint'
sgl|'application/vnd.stardivision.writer-global'
m3a|'audio/mpeg'
opml|'text/x-opml'
pps|'application/vnd.ms-powerpoint'
m4p|'application/mp4'
m4a|'audio/mp4'
lua|'text/x-lua'
luac|'application/x-lua-bytecode'
markdown|'text/x-markdown'
md|'text/x-markdown'
mkd|'text/x-markdown'
ini|'text/plain'
mdp|'application/dash+xml'
map|'application/json'
xsd|'application/xml'
opus|'audio/ogg'
gz|'application/x-gzip'
