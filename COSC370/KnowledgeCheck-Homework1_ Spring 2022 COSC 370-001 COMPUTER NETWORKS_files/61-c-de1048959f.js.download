(window["canvasWebpackJsonp"]=window["canvasWebpackJsonp"]||[]).push([[61],{"6NVu":function(e,n,t){"use strict"
t.d(n,"a",(function(){return o}))
var a=t("IxAH")
const r={true:true,false:false,null:null}
function o(e,n){if(!e||"boolean"===typeof e){const e=window.location.search
if(!e)return{}
return o(e,...arguments)}const t={}
e.replace(/\+/g," ").split("&").forEach(e=>{let[a,o]=e.split("=")
a=decodeURIComponent(a)
o=decodeURIComponent(o)
n&&(o=o&&!isNaN(o)?+o:"undefined"===o?void 0:void 0!==r[o]?r[o]:o)
t[a]=o})
return Object(a["a"])(t)}},IxAH:function(e,n,t){"use strict"
t.d(n,"a",(function(){return o}))
var a=t("Y/W1")
var r=t.n(a)
function o(e){return r()(e).reduce((e,n,t)=>{let a=t.split("][")
let o=a.length-1
if(/\[/.test(a[0])&&/\]$/.test(a[o])){a[o]=a[o].replace(/\]$/,"")
a=a.shift().split("[").concat(a)
o=a.length-1}else o=0
if(o){let r=0
let i=e
while(r<=o){t=""===a[r]?i.length:a[r]
i=i[t]=r<o?i[t]||(a[r+1]&&isNaN(a[r+1])?{}:[]):n
r++}}else r.a.isArray(e[t])?e[t].push(n):null!=e[t]?e[t]=[e[t],n]:e[t]=n
return e},Object.create(null))}},TvTI:function(e,n,t){"use strict"
var a=t("ouhR")
var r=t.n(a)
var o=t("gI0r")
t("8JEM")
r.a.fn.fillTemplateData=function(e){if(this.length&&e){e.iterator&&this.find("*").andSelf().each((function(){const n=r()(this)
r.a.each(["name","id","class"],(t,a)=>{n.attr(a)&&n.attr(a,n.attr(a).replace(/-iterator-/,e.iterator))})}))
e.id&&this.attr("id",e.id)
let a=false
if(e.data)for(var n in e.data){if(e.except&&-1!=r.a.inArray(n,e.except))continue
e.data[n]&&e.dataValues&&-1!=r.a.inArray(n,e.dataValues)&&this.data(n,e.data[n].toString())
const i=this.find("."+n)
var t=e.avoid||""
i.each((function(){const i=r()(this)
if(i.length>0&&0===i.closest(t).length){"undefined"!==typeof e.data[n]&&null!==e.data[n]||(e.data[n]="")
if(e.htmlValues&&-1!=r.a.inArray(n,e.htmlValues)){i.html(r.a.raw(e.data[n].toString()))
if(i.hasClass("user_content")){a=true
i.removeClass("enhanced")
i.data("unenhanced_content_html",e.data[n].toString())}}else if("INPUT"==i[0].tagName.toUpperCase())i.val(e.data[n])
else try{const t=e.data[n].toString()
i.html(Object(o["a"])(t))}catch(e){}}}))}e.hrefValues&&e.data&&this.find("a,span[rel]").each((function(){let n,t,a,o=r()(this)
for(const i in e.hrefValues){if(!e.hrefValues.hasOwnProperty(i))continue
const c=e.hrefValues[i]
if(n=o.attr("href")){const t=r.a.replaceTags(n,c,encodeURIComponent(e.data[c]))
const a=o.text()===o.html()?o.text():null
if(n!==t){o.attr("href",t)
a&&o.text(a)}}(t=o.attr("rel"))&&o.attr("rel",r.a.replaceTags(t,c,e.data[c]));(a=o.attr("name"))&&o.attr("name",r.a.replaceTags(a,c,e.data[c]))}}))
a&&r()(document).triggerHandler("user_content_change")}return this}
r.a.fn.fillTemplateData.defaults={htmlValues:null,hrefValues:null}
r.a.fn.getTemplateData=function(e){if(!this.length||!e)return{}
var n,t={}
if(e.textValues){const n=this
e.textValues.forEach(e=>{const o=n.find("."+e.replace(/\[/g,"\\[").replace(/\]/g,"\\]")+":first")
a=r.a.trim(o.text())
"&nbsp;"===o.html()&&(a="")
1===a.length&&160===a.charCodeAt(0)&&(a="")
t[e]=a})}if(e.dataValues)for(n in e.dataValues){var a=this.data(e.dataValues[n])
a&&(t[e.dataValues[n]]=a)}if(e.htmlValues)for(n in e.htmlValues){const o=this.find("."+e.htmlValues[n].replace(/\[/g,"\\[").replace(/\]/g,"\\]")+":first")
a=null
a=o.hasClass("user_content")&&o.data("unenhanced_content_html")?o.data("unenhanced_content_html"):r.a.trim(o.html())
t[e.htmlValues[n]]=a}return t}
r.a.fn.getTemplateValue=function(e,n){const t=r.a.extend({},n,{textValues:[e]})
return this.getTemplateData(t)[e]}},ZbPE:function(e,n,t){"use strict"
t.d(n,"a",(function(){return w}))
var a=t("rePB")
var r=t("1OyB")
var o=t("vuIU")
var i=t("Ji7U")
var c=t("LK+K")
var m=t("q1tI")
var _=t.n(m)
var l=t("17x9")
var d=t.n(l)
var s=t("TSYQ")
var p=t.n(s)
var g=t("J2CL")
var b=t("KgFQ")
var u=t("jtGx")
var f=t("nAyT")
var y=t("VTBJ")
function h(e){var n=e.typography,t=e.colors,a=e.spacing
return Object(y["a"])({},n,{primaryInverseColor:t.textLightest,primaryColor:t.textDarkest,secondaryColor:t.textDark,secondaryInverseColor:t.textLight,warningColor:t.textWarning,brandColor:t.textBrand,errorColor:t.textDanger,dangerColor:t.textDanger,successColor:t.textSuccess,alertColor:t.textAlert,paragraphMargin:"".concat(a.medium," 0")})}h.canvas=function(e){return{primaryColor:e["ic-brand-font-color-dark"],brandColor:e["ic-brand-primary"]}}
var R,k,v,B
var G={componentId:"enRcg",template:function(e){return"\n\n.enRcg_bGBk{font-family:".concat(e.fontFamily||"inherit","}\n\n.enRcg_bGBk sub,.enRcg_bGBk sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}\n\n.enRcg_bGBk sup{top:-0.4em}\n\n.enRcg_bGBk sub{bottom:-0.4em}\n\n.enRcg_bGBk code,.enRcg_bGBk pre{all:initial;animation:none 0s ease 0s 1 normal none running;backface-visibility:visible;background:transparent none repeat 0 0/auto auto padding-box border-box scroll;border:medium none currentColor;border-collapse:separate;border-image:none;border-radius:0;border-spacing:0;bottom:auto;box-shadow:none;box-sizing:content-box;caption-side:top;clear:none;clip:auto;color:#000;column-count:auto;column-fill:balance;column-gap:normal;column-rule:medium none currentColor;column-span:1;column-width:auto;columns:auto;content:normal;counter-increment:none;counter-reset:none;cursor:auto;direction:ltr;display:inline;empty-cells:show;float:none;font-family:serif;font-family:").concat(e.fontFamilyMonospace||"inherit",";font-size:medium;font-stretch:normal;font-style:normal;font-variant:normal;font-weight:400;height:auto;hyphens:none;left:auto;letter-spacing:normal;line-height:normal;list-style:disc outside none;margin:0;max-height:none;max-width:none;min-height:0;min-width:0;opacity:1;orphans:2;outline:medium none invert;overflow:visible;overflow-x:visible;overflow-y:visible;padding:0;page-break-after:auto;page-break-before:auto;page-break-inside:auto;perspective:none;perspective-origin:50% 50%;position:static;right:auto;tab-size:8;table-layout:auto;text-align:left;text-align-last:auto;text-decoration:none;text-indent:0;text-shadow:none;text-transform:none;top:auto;transform:none;transform-origin:50% 50% 0;transform-style:flat;transition:none 0s ease 0s;unicode-bidi:normal;vertical-align:baseline;visibility:visible;white-space:normal;widows:2;width:auto;word-spacing:normal;z-index:auto}\n\n.enRcg_bGBk em,.enRcg_bGBk i{font-style:italic}\n\n.enRcg_bGBk b,.enRcg_bGBk strong{font-weight:").concat(e.fontWeightBold||"inherit","}\n\n.enRcg_bGBk p{display:block;margin:").concat(e.paragraphMargin||"inherit",";padding:0}\n\ninput.enRcg_bGBk[type]{-moz-appearance:none;-webkit-appearance:none;appearance:none;background:none;border:none;border-radius:0;box-shadow:none;box-sizing:border-box;color:inherit;display:block;height:auto;line-height:inherit;margin:0;outline:0;padding:0;text-align:start;width:100%}\n\n[dir=ltr] input.enRcg_bGBk[type]{text-align:left}\n\n[dir=rtl] input.enRcg_bGBk[type]{text-align:right}\n\n.enRcg_bGBk:focus,input.enRcg_bGBk[type]:focus{outline:none}\n\n.enRcg_bGBk.enRcg_qFsi,input.enRcg_bGBk[type].enRcg_qFsi{color:").concat(e.primaryColor||"inherit","}\n\n.enRcg_bGBk.enRcg_bLsb,input.enRcg_bGBk[type].enRcg_bLsb{color:").concat(e.secondaryColor||"inherit","}\n\n.enRcg_bGBk.enRcg_ezBQ,input.enRcg_bGBk[type].enRcg_ezBQ{color:").concat(e.primaryInverseColor||"inherit","}\n\n.enRcg_bGBk.enRcg_dlnd,input.enRcg_bGBk[type].enRcg_dlnd{color:").concat(e.secondaryInverseColor||"inherit","}\n\n.enRcg_bGBk.enRcg_cJLh,input.enRcg_bGBk[type].enRcg_cJLh{color:").concat(e.successColor||"inherit","}\n\n.enRcg_bGBk.enRcg_fpfC,input.enRcg_bGBk[type].enRcg_fpfC{color:").concat(e.brandColor||"inherit","}\n\n.enRcg_bGBk.enRcg_eHcp,input.enRcg_bGBk[type].enRcg_eHcp{color:").concat(e.warningColor||"inherit","}\n\n.enRcg_bGBk.enRcg_dwua,input.enRcg_bGBk[type].enRcg_dwua{color:").concat(e.errorColor||"inherit","}\n\n.enRcg_bGBk.enRcg_NQMb,input.enRcg_bGBk[type].enRcg_NQMb{color:").concat(e.dangerColor||"inherit","}\n\n.enRcg_bGBk.enRcg_eZgl,input.enRcg_bGBk[type].enRcg_eZgl{color:").concat(e.alertColor||"inherit","}\n\n.enRcg_bGBk.enRcg_fbNi,input.enRcg_bGBk[type].enRcg_fbNi{-ms-hyphens:auto;-webkit-hyphens:auto;hyphens:auto;overflow-wrap:break-word;word-break:break-word}\n\n.enRcg_bGBk.enRcg_drST,input.enRcg_bGBk[type].enRcg_drST{font-weight:").concat(e.fontWeightNormal||"inherit","}\n\n.enRcg_bGBk.enRcg_pEgL,input.enRcg_bGBk[type].enRcg_pEgL{font-weight:").concat(e.fontWeightLight||"inherit","}\n\n.enRcg_bGBk.enRcg_bdMA,input.enRcg_bGBk[type].enRcg_bdMA{font-weight:").concat(e.fontWeightBold||"inherit","}\n\n.enRcg_bGBk.enRcg_ijuF,input.enRcg_bGBk[type].enRcg_ijuF{font-style:normal}\n\n.enRcg_bGBk.enRcg_fetN,input.enRcg_bGBk[type].enRcg_fetN{font-style:italic}\n\n.enRcg_bGBk.enRcg_dfBC,input.enRcg_bGBk[type].enRcg_dfBC{font-size:").concat(e.fontSizeXSmall||"inherit","}\n\n.enRcg_bGBk.enRcg_doqw,input.enRcg_bGBk[type].enRcg_doqw{font-size:").concat(e.fontSizeSmall||"inherit","}\n\n.enRcg_bGBk.enRcg_ycrn,input.enRcg_bGBk[type].enRcg_ycrn{font-size:").concat(e.fontSizeMedium||"inherit","}\n\n.enRcg_bGBk.enRcg_cMDj,input.enRcg_bGBk[type].enRcg_cMDj{font-size:").concat(e.fontSizeLarge||"inherit","}\n\n.enRcg_bGBk.enRcg_eoMd,input.enRcg_bGBk[type].enRcg_eoMd{font-size:").concat(e.fontSizeXLarge||"inherit","}\n\n.enRcg_bGBk.enRcg_fdca,input.enRcg_bGBk[type].enRcg_fdca{font-size:").concat(e.fontSizeXXLarge||"inherit","}\n\n.enRcg_bGBk.enRcg_fEWX,input.enRcg_bGBk[type].enRcg_fEWX{line-height:").concat(e.lineHeight||"inherit","}\n\n.enRcg_bGBk.enRcg_fNIu,input.enRcg_bGBk[type].enRcg_fNIu{line-height:").concat(e.lineHeightFit||"inherit","}\n\n.enRcg_bGBk.enRcg_dfDs,input.enRcg_bGBk[type].enRcg_dfDs{line-height:").concat(e.lineHeightCondensed||"inherit","}\n\n.enRcg_bGBk.enRcg_bDjL,input.enRcg_bGBk[type].enRcg_bDjL{line-height:").concat(e.lineHeightDouble||"inherit","}\n\n.enRcg_bGBk.enRcg_eQnG,input.enRcg_bGBk[type].enRcg_eQnG{letter-spacing:").concat(e.letterSpacingNormal||"inherit","}\n\n.enRcg_bGBk.enRcg_bbUA,input.enRcg_bGBk[type].enRcg_bbUA{letter-spacing:").concat(e.letterSpacingCondensed||"inherit","}\n\n.enRcg_bGBk.enRcg_bRWU,input.enRcg_bGBk[type].enRcg_bRWU{letter-spacing:").concat(e.letterSpacingExpanded||"inherit","}\n\n.enRcg_bGBk.enRcg_wZsr,input.enRcg_bGBk[type].enRcg_wZsr{text-transform:none}\n\n.enRcg_bGBk.enRcg_fCZK,input.enRcg_bGBk[type].enRcg_fCZK{text-transform:capitalize}\n\n.enRcg_bGBk.enRcg_dsRi,input.enRcg_bGBk[type].enRcg_dsRi{text-transform:uppercase}\n\n.enRcg_bGBk.enRcg_bLtD,input.enRcg_bGBk[type].enRcg_bLtD{text-transform:lowercase}")},root:"enRcg_bGBk","color-primary":"enRcg_qFsi","color-secondary":"enRcg_bLsb","color-primary-inverse":"enRcg_ezBQ","color-secondary-inverse":"enRcg_dlnd","color-success":"enRcg_cJLh","color-brand":"enRcg_fpfC","color-warning":"enRcg_eHcp","color-error":"enRcg_dwua","color-danger":"enRcg_NQMb","color-alert":"enRcg_eZgl","wrap-break-word":"enRcg_fbNi","weight-normal":"enRcg_drST","weight-light":"enRcg_pEgL","weight-bold":"enRcg_bdMA","style-normal":"enRcg_ijuF","style-italic":"enRcg_fetN","x-small":"enRcg_dfBC",small:"enRcg_doqw",medium:"enRcg_ycrn",large:"enRcg_cMDj","x-large":"enRcg_eoMd","xx-large":"enRcg_fdca","lineHeight-default":"enRcg_fEWX","lineHeight-fit":"enRcg_fNIu","lineHeight-condensed":"enRcg_dfDs","lineHeight-double":"enRcg_bDjL","letterSpacing-normal":"enRcg_eQnG","letterSpacing-condensed":"enRcg_bbUA","letterSpacing-expanded":"enRcg_bRWU","transform-none":"enRcg_wZsr","transform-capitalize":"enRcg_fCZK","transform-uppercase":"enRcg_dsRi","transform-lowercase":"enRcg_bLtD"}
var w=(R=Object(g["l"])(h,G),R(k=(B=v=function(e){Object(i["a"])(t,e)
var n=Object(c["a"])(t)
function t(){Object(r["a"])(this,t)
return n.apply(this,arguments)}Object(o["a"])(t,[{key:"render",value:function(){var e
var n=this.props,r=n.wrap,o=n.weight,i=n.fontStyle,c=n.size,m=n.lineHeight,l=n.letterSpacing,d=n.transform,s=n.color,g=n.children
var f=Object(b["a"])(t,this.props)
return _.a.createElement(f,Object.assign({},Object(u["b"])(this.props),{className:p()((e={},Object(a["a"])(e,G.root,true),Object(a["a"])(e,G[c],c),Object(a["a"])(e,G["wrap-".concat(r)],r),Object(a["a"])(e,G["weight-".concat(o)],o),Object(a["a"])(e,G["style-".concat(i)],i),Object(a["a"])(e,G["transform-".concat(d)],d),Object(a["a"])(e,G["lineHeight-".concat(m)],m),Object(a["a"])(e,G["letterSpacing-".concat(l)],l),Object(a["a"])(e,G["color-".concat(s)],s),e)),ref:this.props.elementRef}),g)}}])
t.displayName="Text"
return t}(m["Component"]),v.propTypes={as:d.a.elementType,children:d.a.node,color:f["a"].deprecatePropValues(d.a.oneOf(["primary","secondary","brand","success","warning","error","danger","alert","primary-inverse","secondary-inverse"]),["error"],"It will be removed in version 8.0.0. Use `danger` instead."),elementRef:d.a.func,fontStyle:d.a.oneOf(["italic","normal"]),letterSpacing:d.a.oneOf(["normal","condensed","expanded"]),lineHeight:d.a.oneOf(["default","fit","condensed","double"]),size:d.a.oneOf(["x-small","small","medium","large","x-large","xx-large"]),transform:d.a.oneOf(["none","capitalize","uppercase","lowercase"]),weight:d.a.oneOf(["normal","light","bold"]),wrap:d.a.oneOf(["normal","break-word"])},v.defaultProps={as:"span",wrap:"normal",size:"medium",letterSpacing:"normal",children:null,elementRef:void 0,color:void 0,transform:void 0,lineHeight:void 0,fontStyle:void 0,weight:void 0},B))||k)},bbn0:function(e,n,t){"use strict"
var a=t("HGxv")
var r=t("8WeW")
Object(r["a"])(JSON.parse('{"ar":{"play_media_comment_35257210":"تشغيل تعليق الوسائط.","play_media_comment_by_name_from_createdat_515b3b":"تشغيل تعليق الوسائط بواسطة %{name} من %{createdAt}."},"ca":{"play_media_comment_35257210":"Reprodueix el comentari multimèdia.","play_media_comment_by_name_from_createdat_515b3b":"Reprodueix el comentari multimèdia de %{name} enviat el %{createdAt}."},"cy":{"play_media_comment_35257210":"Chwarae sylw ar gyfryngau.","play_media_comment_by_name_from_createdat_515b3b":"Chwarae sylw ar gyfryngau gan %{name} o %{createdAt}."},"da":{"play_media_comment_35257210":"Afspil medie kommentar.","play_media_comment_by_name_from_createdat_515b3b":"Afspil mediekommentar af %{name} fra %{createdAt}."},"da-x-k12":{"play_media_comment_35257210":"Afspil medie kommentar.","play_media_comment_by_name_from_createdat_515b3b":"Afspil mediekommentar af %{name} fra %{createdAt}."},"de":{"play_media_comment_35257210":"Medienkommentar wiedergeben","play_media_comment_by_name_from_createdat_515b3b":"Medienkommentar durch %{name} von %{createdAt} wiedergeben."},"en-AU":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"en-AU-x-unimelb":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"en-CA":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"en-GB":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"en-GB-x-lbs":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"en-GB-x-ukhe":{"play_media_comment_35257210":"Play media comment.","play_media_comment_by_name_from_createdat_515b3b":"Play media comment by %{name} from %{createdAt}."},"es":{"play_media_comment_35257210":"Reproducir comentario de multimedia.","play_media_comment_by_name_from_createdat_515b3b":"Reproducir comentario de multimedia de %{name} desde %{createdAt}."},"es-ES":{"play_media_comment_35257210":"Reproducir comentario multimedia.","play_media_comment_by_name_from_createdat_515b3b":"Reproducir comentario multimedia de %{name} desde %{createdAt}."},"fa":{"play_media_comment_35257210":"پخش نظر رسانه ای","play_media_comment_by_name_from_createdat_515b3b":" نظر رسانه‌ای %{name} را  از %{createdAt} پخش کنید."},"fi":{"play_media_comment_35257210":"Toista mediakommentti.","play_media_comment_by_name_from_createdat_515b3b":"Toista mediakommentti %{name} kohteesta %{createdAt}."},"fr":{"play_media_comment_35257210":"Lancer le commentaire sur média.","play_media_comment_by_name_from_createdat_515b3b":"Lancer le commentaire sur média par %{name} à partir de %{createdAt}."},"fr-CA":{"play_media_comment_35257210":"Lire le commentaire du support","play_media_comment_by_name_from_createdat_515b3b":"Lire le commentaire du support par %{name} du %{createdAt}."},"ht":{"play_media_comment_35257210":"Jwe kòmantè medya.","play_media_comment_by_name_from_createdat_515b3b":"Jwe kòmantè medya pa %{name} de %{createdAt}."},"is":{"play_media_comment_35257210":"Spila miðilsathugasemd.","play_media_comment_by_name_from_createdat_515b3b":"Spila miðilsathugasemd eftir %{name} frá %{createdAt}."},"it":{"play_media_comment_35257210":"Commento sulla riproduzione del contenuto multimediale.","play_media_comment_by_name_from_createdat_515b3b":"Commento sulla riproduzione del contenuto multimediale da parte di %{name} da %{createdAt}."},"ja":{"play_media_comment_35257210":"メディア コメントの再生。","play_media_comment_by_name_from_createdat_515b3b":"%{name}まで%{createdAt}からのメディアのコメントを再生します。"},"mi":{"play_media_comment_35257210":"Mahia ngā korero pāpāho","play_media_comment_by_name_from_createdat_515b3b":"Mahia ngā korero pāpāho ma %{name} mai te %{createdAt}."},"nb":{"play_media_comment_35257210":"Spill mediainnhold","play_media_comment_by_name_from_createdat_515b3b":"Spill mediainnhold av %{name} fra %{createdAt}."},"nb-x-k12":{"play_media_comment_35257210":"Spill mediainnhold","play_media_comment_by_name_from_createdat_515b3b":"Spill mediainnhold av %{name} fra %{createdAt}."},"nl":{"play_media_comment_35257210":"Media-opmerking afspelen","play_media_comment_by_name_from_createdat_515b3b":"Speel media-opmerking door %{name} van %{createdAt} af."},"nn":{"play_media_comment_35257210":"Spel av medieinnhald.","play_media_comment_by_name_from_createdat_515b3b":"Spel av mediekommentar frå %{name} den %{createdAt}."},"pl":{"play_media_comment_35257210":"Odtwórz komentarz multimedialny.","play_media_comment_by_name_from_createdat_515b3b":"Odtwórz komentarz multimedialny %{name} z %{createdAt}."},"pt":{"play_media_comment_35257210":"Reproduzir comentário de mídia.","play_media_comment_by_name_from_createdat_515b3b":"Reproduzir comentários de mídia %{name} de %{createdAt}."},"pt-BR":{"play_media_comment_35257210":"Reproduzir comentário em mídia.","play_media_comment_by_name_from_createdat_515b3b":"Reproduzir comentário em mídia por %{name} de %{createdAt}."},"ru":{"play_media_comment_35257210":"Воспроизведение мультимедийного комментария.","play_media_comment_by_name_from_createdat_515b3b":"Воспроизвести мультимедийный комментарии %{name} из %{createdAt}."},"sl":{"play_media_comment_35257210":"Predvajaj komentar v obliki medija.","play_media_comment_by_name_from_createdat_515b3b":"Predvajaj komentar v obliki medija %{name}, ki je bil ustvarjen ob/dne %{createdAt}."},"sv":{"play_media_comment_35257210":"Spela upp mediekommentar.","play_media_comment_by_name_from_createdat_515b3b":"Spela upp mediekommentar av %{name} från %{createdAt}."},"sv-x-k12":{"play_media_comment_35257210":"Spela upp mediekommentar.","play_media_comment_by_name_from_createdat_515b3b":"Spela upp mediekommentar av %{name} från %{createdAt}."},"th":{"play_media_comment_35257210":"เปิดเล่นความเห็นแบบสื่อ","play_media_comment_by_name_from_createdat_515b3b":"เปิดเล่นความเห็นแบบสื่อโดย %{name} จาก %{createdAt}"},"zh-Hans":{"play_media_comment_35257210":"播放媒体评论。","play_media_comment_by_name_from_createdat_515b3b":"播放%{name}的来自%{createdAt}的媒体评论。"},"zh-Hant":{"play_media_comment_35257210":"播放媒體評論。","play_media_comment_by_name_from_createdat_515b3b":"播放%{name}於%{createdAt}創建的媒體評論。"}}'))
t("jQeR")
t("0sPK")
var o=a["default"].scoped("mediaCommentThumbnail")
var i=t("Y/W1")
var c=t.n(i)
var m=t("gI0r")
var _=t("ouhR")
var l=t.n(_)
var d=t("6NVu")
const s={normal:{width:140,height:100},small:{width:70,height:50}}
function p(e,n,t){if(!INST.kalturaSettings)return console.log("Kaltura has not been enabled for this account")
let a,r
const i=l()(e)
try{const e=document.createElement("a")
e.href=i.attr("href")
r=e}catch(e){}if(r&&Object(d["a"])(r.search).no_preview)return
const c=s[n]||s.normal
const _=i.data("media_comment_id")||l.a.trim(i.find(".media_comment_id:first").text())||(a=i.attr("id"))&&a.match(/^media_comment_/)&&a.substring(14)||l.a.trim(i.parent().find(".media_comment_id:first").text())
const p=i.data("author")
const g=i.data("created_at")
let b
b=p&&g?o.t("Play media comment by %{name} from %{createdAt}.",{name:p,createdAt:g}):o.t("Play media comment.")
if(_){const e="https://"+INST.kalturaSettings.resource_domain
const a=`${e}/p/${INST.kalturaSettings.partner_id}/thumbnail/entry_id/${_}/width/${c.width}/height/${c.height}/bgcolor/000000/type/2/vid_sec/5`
const r=l()(`<span\n        style='background-image: url(${Object(m["a"])(a)});'\n        class='media_comment_thumbnail media_comment_thumbnail-${Object(m["a"])(n)}'\n      >\n        <span class='media_comment_thumbnail_play_button'>\n          <span class='screenreader-only'>\n            ${Object(m["a"])(b)}\n          </span>\n        </span>\n      </span>`)
const o=i.closest("p")
o.attr("title")||o.attr("title",Object(m["a"])(b))
let d=i
if(t){d=i.clone().empty().removeClass("instructure_file_link")
const e=i.parent(".instructure_file_link_holder")
e.length?d.appendTo(e):i.after(d)}else i.empty()
d.data("download",d.attr("href")).prop("href","#").addClass("instructure_inline_media_comment").append(r).css({backgroundImage:"",padding:0})}}l.a.fn.mediaCommentThumbnail=function(e="normal",n){return this.each((function(){c.a.defer(p,this,e,n)}))}}}])

//# sourceMappingURL=61-c-de1048959f.js.map