(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(e){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c("jscomp_symbol_"+(e||"")+"_"+d++,e)}
function c(e,f){this.h=e;ba(this,"description",{configurable:!0,writable:!0,value:f})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ja=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ka;
if("function"==typeof Object.setPrototypeOf)ka=Object.setPrototypeOf;else{var ma;a:{var na={a:!0},oa={};try{oa.__proto__=na;ma=oa.a;break a}catch(a){}ma=!1}ka=ma?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var pa=ka;
function v(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(pa)pa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.H=b.prototype}
function qa(){this.m=!1;this.l=null;this.i=void 0;this.h=1;this.A=this.j=0;this.o=null}
function ra(a){if(a.m)throw new TypeError("Generator is already running");a.m=!0}
qa.prototype.u=function(a){this.i=a};
function sa(a,b){a.o={va:b,Pa:!0};a.h=a.j||a.A}
qa.prototype.return=function(a){this.o={return:a};this.h=this.A};
function x(a,b,c){a.h=c;return{value:b}}
function ta(a){a.j=0;var b=a.o.va;a.o=null;return b}
function ua(a){this.h=new qa;this.i=a}
function va(a,b){ra(a.h);var c=a.h.l;if(c)return wa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return xa(a)}
function wa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.m=!1,e;var f=e.value}catch(g){return a.h.l=null,sa(a.h,g),xa(a)}a.h.l=null;d.call(a.h,f);return xa(a)}
function xa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.m=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,sa(a.h,c)}a.h.m=!1;if(a.h.o){b=a.h.o;a.h.o=null;if(b.Pa)throw b.va;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function ya(a){this.next=function(b){ra(a.h);a.h.l?b=wa(a,a.h.l.next,b,a.h.u):(a.h.u(b),b=xa(a));return b};
this.throw=function(b){ra(a.h);a.h.l?b=wa(a,a.h.l["throw"],b,a.h.u):(sa(a.h,b),b=xa(a));return b};
this.return=function(b){return va(a,b)};
this[Symbol.iterator]=function(){return this}}
function za(a,b){b=new ya(new ua(b));pa&&a.prototype&&pa(b,a.prototype);return b}
t("Reflect",function(a){return a?a:{}});
t("Reflect.construct",function(){return ja});
t("Reflect.setPrototypeOf",function(a){return a?a:pa?function(b,c){try{return pa(b,c),!0}catch(d){return!1}}:null});
function Aa(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Aa(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Aa(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Object.setPrototypeOf",function(a){return a||pa});
function Ba(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var Ca="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ba(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||Ca});
t("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.u=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.o()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.o=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(p){k||(k=!0,l.call(h,p))}}
var h=this,k=!1;return{resolve:g(this.J),reject:g(this.o)}};
b.prototype.J=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.S(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.I(g):this.m(g)}};
b.prototype.I=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.T(h,g):this.m(g)};
b.prototype.o=function(g){this.A(2,g)};
b.prototype.m=function(g){this.A(1,g)};
b.prototype.A=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.K();this.C()};
b.prototype.K=function(){var g=this;e(function(){if(g.F()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.F=function(){if(this.u)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.S=function(g){var h=this.l();g.ca(h.resolve,h.reject)};
b.prototype.T=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(q,r){return"function"==typeof q?function(w){try{l(q(w))}catch(z){p(z)}}:r}
var l,p,n=new b(function(q,r){l=q;p=r});
this.ca(k(g,l),k(h,p));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ca=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),p=l.next();!p.done;p=l.next())d(p.value).ca(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,p){function n(w){return function(z){q[w]=z;r--;0==r&&l(q)}}
var q=[],r=0;do q.push(void 0),r++,d(k.value).ca(n(q.length-1),p),k=h.next();while(!k.done)})};
return b});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Aa(this,b,"includes").indexOf(b,c||0)}});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ba(b,d)&&c.push([d,b[d]]);return c}});
function Da(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.keys",function(a){return a?a:function(){return Da(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Da(this,function(b,c){return c})}});
t("Array.prototype.entries",function(a){return a?a:function(){return Da(this,function(b,c){return[b,c]})}});
t("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ba(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(p){if(p instanceof c)return p;Object.isExtensible(p)&&e(p);return l(p)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),p=new a([[k,2],[l,3]]);if(2!=p.get(k)||3!=p.get(l))return!1;p.delete(k);p.set(l,4);return!p.has(k)&&4==p.get(l)}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ba(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Ba(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.h)?delete k[g][this.h]:!1};
return b});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ea(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var p=h.i[l];if(p&&Ba(h.i,l))for(h=0;h<p.length;h++){var n=p[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:p,index:h,G:n}}return{id:l,list:p,index:-1,G:void 0}}
function e(h){this.i={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),p=l.next();if(p.done||p.value[0]!=h||"s"!=p.value[1])return!1;p=l.next();return p.done||4!=p.value[0].x||"t"!=p.value[1]||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.i[l.id]=[]);l.G?l.G.value=k:(l.G={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.G),this.h.previous.next=l.G,this.h.previous=l.G,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.G&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.i[h.id],h.G.previous.next=h.G.next,h.G.next.previous=h.G.previous,h.G.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.i={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).G};
e.prototype.get=function(h){return(h=d(this,h).G)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),p;!(p=l.next()).done;)p=p.value,h.call(k,p[1],p[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
t("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Ba(b,d)&&c.push(b[d]);return c}});
var y=this||self;function A(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Ea(a){if(a&&a!=y)return Fa(a.document);null===Ga&&(Ga=Fa(y.document));return Ga}
var Ha=/^[\w+/_-]+[=]{0,2}$/,Ga=null;function Fa(a){return(a=a.querySelector&&a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Ha.test(a)?a:""}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ia(){}
function Ja(a){a.la=void 0;a.getInstance=function(){return a.la?a.la:a.la=new a}}
function Ka(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function La(a){var b=Ka(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function C(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ma(a){return Object.prototype.hasOwnProperty.call(a,Na)&&a[Na]||(a[Na]=++Oa)}
var Na="closure_uid_"+(1E9*Math.random()>>>0),Oa=0;function Pa(a,b,c){return a.call.apply(a.bind,arguments)}
function Qa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function E(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?E=Pa:E=Qa;return E.apply(null,arguments)}
function Ra(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Sa(a,b){A(a,b,void 0)}
function F(a,b){function c(){}
c.prototype=b.prototype;a.H=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.wk=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ta(a){return a}
;function Va(a){if(Error.captureStackTrace)Error.captureStackTrace(this,Va);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
F(Va,Error);Va.prototype.name="CustomError";function Wa(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Xa(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Ya=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},G=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Za=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},$a=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ab=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
G(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function bb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function cb(a,b){b=Ya(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function db(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function eb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(La(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function fb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function gb(a){var b=hb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ib(a){for(var b in a)return!1;return!0}
function jb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function kb(){var a=H("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function lb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function mb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function nb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=nb(a[c]);return b}
var ob="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function pb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ob.length;f++)c=ob[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var qb;function rb(){if(void 0===qb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ta,createScript:Ta,createScriptURL:Ta})}catch(c){y.console&&y.console.error(c.message)}qb=a}else qb=a}return qb}
;function sb(a,b){this.h=b===tb?a:""}
m=sb.prototype;m.W=!0;m.V=function(){return this.h.toString()};
m.ka=!0;m.ha=function(){return 1};
m.toString=function(){return this.h+""};
function ub(a){if(a instanceof sb&&a.constructor===sb)return a.h;Ka(a);return"type_error:TrustedResourceUrl"}
var tb={};var vb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function wb(a,b){if(b)a=a.replace(xb,"&amp;").replace(yb,"&lt;").replace(zb,"&gt;").replace(Ab,"&quot;").replace(Bb,"&#39;").replace(Cb,"&#0;");else{if(!Db.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(xb,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(yb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(zb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(Ab,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(Bb,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(Cb,"&#0;"))}return a}
var xb=/&/g,yb=/</g,zb=/>/g,Ab=/"/g,Bb=/'/g,Cb=/\x00/g,Db=/[\x00&<>"']/;function I(a,b){this.h=b===Eb?a:""}
m=I.prototype;m.W=!0;m.V=function(){return this.h.toString()};
m.ka=!0;m.ha=function(){return 1};
m.toString=function(){return this.h.toString()};
function Fb(a){if(a instanceof I&&a.constructor===I)return a.h;Ka(a);return"type_error:SafeUrl"}
var Gb=/^(?:audio\/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font\/\w+|image\/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video\/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\w+=(?:\w+|"[\w;,= ]+"))*$/i,Hb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Ib=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;function Jb(a){if(a instanceof I)return a;a="object"==typeof a&&a.W?a.V():String(a);Ib.test(a)||(a="about:invalid#zClosurez");return new I(a,Eb)}
var Eb={},Kb=new I("about:invalid#zClosurez",Eb);var Lb;a:{var Mb=y.navigator;if(Mb){var Nb=Mb.userAgent;if(Nb){Lb=Nb;break a}}Lb=""}function J(a){return-1!=Lb.indexOf(a)}
;function Ob(a,b,c){this.h=c===Pb?a:"";this.i=b}
m=Ob.prototype;m.ka=!0;m.ha=function(){return this.i};
m.W=!0;m.V=function(){return this.h.toString()};
m.toString=function(){return this.h.toString()};
var Pb={};function Qb(a,b){var c=rb();a=c?c.createHTML(a):a;return new Ob(a,b,Pb)}
;function Rb(a,b){b=b instanceof I?b:Jb(b);a.href=Fb(b)}
function Sb(a,b){a.src=ub(b);(b=Ea(a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
;function Tb(a){return a=wb(a,void 0)}
function Ub(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Vb=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^\\/?#]*)@)?([^\\/?#]*?)(?::([0-9]+))?(?=[\\/?#]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function Wb(a){return a?decodeURI(a):a}
function Xb(a){return Wb(a.match(Vb)[3]||null)}
function Yb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Yb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Zb(a){var b=[],c;for(c in a)Yb(c,a[c],b);return b.join("&")}
function $b(a,b){b=Zb(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var ac=/#|$/;function bc(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function cc(){return J("iPhone")&&!J("iPod")&&!J("iPad")}
;function dc(a){dc[" "](a);return a}
dc[" "]=Ia;var ec=J("Opera"),fc=J("Trident")||J("MSIE"),gc=J("Edge"),hc=J("Gecko")&&!(-1!=Lb.toLowerCase().indexOf("webkit")&&!J("Edge"))&&!(J("Trident")||J("MSIE"))&&!J("Edge"),ic=-1!=Lb.toLowerCase().indexOf("webkit")&&!J("Edge");function jc(){var a=y.document;return a?a.documentMode:void 0}
var kc;a:{var lc="",mc=function(){var a=Lb;if(hc)return/rv:([^\);]+)(\)|;)/.exec(a);if(gc)return/Edge\/([\d\.]+)/.exec(a);if(fc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(ic)return/WebKit\/(\S+)/.exec(a);if(ec)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
mc&&(lc=mc?mc[1]:"");if(fc){var nc=jc();if(null!=nc&&nc>parseFloat(lc)){kc=String(nc);break a}}kc=lc}var oc=kc,pc;if(y.document&&fc){var qc=jc();pc=qc?qc:parseInt(oc,10)||void 0}else pc=void 0;var rc=pc;var sc=cc()||J("iPod"),tc=J("iPad"),uc=J("Safari")&&!((J("Chrome")||J("CriOS"))&&!J("Edge")||J("Coast")||J("Opera")||J("Edge")||J("Edg/")||J("OPR")||J("Firefox")||J("FxiOS")||J("Silk")||J("Android"))&&!(cc()||J("iPad")||J("iPod"));var vc={},wc=null;
function xc(a){var b=3;La(a);void 0===b&&(b=0);if(!wc){wc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));vc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===wc[h]&&(wc[h]=g)}}}b=vc[b];c=[];for(d=0;d<a.length;d+=3){var k=a[d],l=(e=d+1<a.length)?a[d+1]:0;h=(f=d+2<a.length)?a[d+2]:0;g=k>>2;k=(k&3)<<4|l>>4;l=(l&15)<<2|h>>6;h&=63;f||(h=64,e||(l=64));c.push(b[g],b[k],b[l]||"",b[h]||"")}return c.join("")}
;var K=window;var yc=!fc||9<=Number(rc);function zc(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=zc.prototype;m.clone=function(){return new zc(this.x,this.y)};
m.equals=function(a){return a instanceof zc&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};function Ac(a,b){this.width=a;this.height=b}
m=Ac.prototype;m.clone=function(){return new Ac(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Bc(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Cc(a,b){fb(b,function(c,d){c&&"object"==typeof c&&c.W&&(c=c.V());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:Dc.hasOwnProperty(d)?a.setAttribute(Dc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var Dc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};
function Ec(a,b,c){var d=arguments,e=document,f=String(d[0]),g=d[1];if(!yc&&g&&(g.name||g.type)){f=["<",f];g.name&&f.push(' name="',Tb(g.name),'"');if(g.type){f.push(' type="',Tb(g.type),'"');var h={};pb(h,g);delete h.type;g=h}f.push(">");f=f.join("")}f=Fc(e,f);g&&("string"===typeof g?f.className=g:Array.isArray(g)?f.className=g.join(" "):Cc(f,g));2<d.length&&Gc(e,f,d);return f}
function Gc(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!La(f)||C(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(C(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}G(g?db(f):f,d)}}}
function Fc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Hc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Ic(a){var b=Jc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Kc(){var a=[];Ic(function(b){a.push(b)});
return a}
var Jc={rb:"allow-forms",sb:"allow-modals",tb:"allow-orientation-lock",ub:"allow-pointer-lock",vb:"allow-popups",wb:"allow-popups-to-escape-sandbox",xb:"allow-presentation",yb:"allow-same-origin",zb:"allow-scripts",Ab:"allow-top-navigation",Bb:"allow-top-navigation-by-user-activation"},Lc=Xa(function(){return Kc()});
function Mc(){var a=Fc(document,"IFRAME"),b={};G(Lc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;function Nc(a){Oc();var b=rb();a=b?b.createScriptURL(a):a;return new sb(a,tb)}
var Oc=Ia;function Pc(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Qc=(new Date).getTime();function Rc(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Sc(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;p=l=0}
function b(n){for(var q=g,r=0;64>r;r+=4)q[r/4]=n[r]<<24|n[r+1]<<16|n[r+2]<<8|n[r+3];for(r=16;80>r;r++)n=q[r-3]^q[r-8]^q[r-14]^q[r-16],q[r]=(n<<1|n>>>31)&4294967295;n=e[0];var w=e[1],z=e[2],D=e[3],P=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var ia=D^w&(z^D);var la=1518500249}else ia=w^z^D,la=1859775393;else 60>r?(ia=w&z|D&(w|z),la=2400959708):(ia=w^z^D,la=3395469782);ia=((n<<5|n>>>27)&4294967295)+ia+P+la+q[r]&4294967295;P=D;D=z;z=(w<<30|w>>>2)&4294967295;w=n;n=ia}e[0]=e[0]+n&4294967295;e[1]=e[1]+w&4294967295;
e[2]=e[2]+z&4294967295;e[3]=e[3]+D&4294967295;e[4]=e[4]+P&4294967295}
function c(n,q){if("string"===typeof n){n=unescape(encodeURIComponent(n));for(var r=[],w=0,z=n.length;w<z;++w)r.push(n.charCodeAt(w));n=r}q||(q=n.length);r=0;if(0==l)for(;r+64<q;)b(n.slice(r,r+64)),r+=64,p+=64;for(;r<q;)if(f[l++]=n[r++],p++,64==l)for(l=0,b(f);r+64<q;)b(n.slice(r,r+64)),r+=64,p+=64}
function d(){var n=[],q=8*p;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=q&255,q>>>=8;b(f);for(r=q=0;5>r;r++)for(var w=24;0<=w;w-=8)n[q++]=e[r]>>w&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,p;a();return{reset:a,update:c,digest:d,Ea:function(){for(var n=d(),q="",r=0;r<n.length;r++)q+="0123456789ABCDEF".charAt(Math.floor(n[r]/16))+"0123456789ABCDEF".charAt(n[r]%16);return q}}}
;function Tc(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,Uc(Rc(d),a,c||null)].join(" "):null}
function Uc(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],G(d,function(h){e.push(h)}),Vc(e.join(" "));
var f=[],g=[];G(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];G(d,function(h){e.push(h)});
a=Vc(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Vc(a){var b=Sc();b.update(a);return b.Ea().toLowerCase()}
;var Wc={};function Xc(a){this.h=a||{cookie:""}}
m=Xc.prototype;m.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ma:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Ek;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ma}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);this.h.cookie=a+"="+b+(f?";domain="+f:"")+(g?";path="+g:"")+(0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString())+(d?";secure":"")+(null!=e?";samesite="+e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=vb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ma:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=vb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Yc=new Xc("undefined"==typeof document?null:document);function Zc(a){return!!Wc.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function $c(a,b,c,d){(a=y[a])||(a=(new Xc(document)).get(b));return a?Tc(a,c,d):null}
function ad(a){var b=void 0===b?!1:b;var c=Rc(String(y.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Zc(e)&&(f=f||y.__1PSAPISID);if(f)e=!0;else{var g=new Xc(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID");Zc(e)&&(f=f||g.get("__Secure-1PAPISID"));e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?y.__SAPISID:y.__APISID,e||(e=new Xc(document),
e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?Tc(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&Zc(b)&&((b=$c("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=$c("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;function bd(){this.h=[];this.i=-1}
bd.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.h[a]!=b&&(this.h[a]=b,this.i=-1)};
bd.prototype.get=function(a){return!!this.h[a]};
function cd(a){-1==a.i&&(a.i=ab(a.h,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function dd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
dd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function ed(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var fd;
function gd(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!J("Presto")&&(a=function(){var e=Fc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=E(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!J("Trident")&&!J("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.ra;c.ra=null;e()}};
return function(e){d.next={ra:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function hd(a){y.setTimeout(function(){throw a;},0)}
;function id(){this.i=this.h=null}
id.prototype.add=function(a,b){var c=jd.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
id.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var jd=new dd(function(){return new kd},function(a){return a.reset()});
function kd(){this.next=this.scope=this.h=null}
kd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
kd.prototype.reset=function(){this.next=this.scope=this.h=null};function ld(a,b){md||nd();od||(md(),od=!0);pd.add(a,b)}
var md;function nd(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);md=function(){a.then(qd)}}else md=function(){var b=qd;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!J("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(fd||(fd=gd()),fd(b)):y.setImmediate(b)}}
var od=!1,pd=new id;function qd(){for(var a;a=pd.remove();){try{a.h.call(a.scope)}catch(b){hd(b)}ed(jd,a)}od=!1}
;function rd(){this.i=-1}
;function sd(){this.i=64;this.h=[];this.m=[];this.u=[];this.l=[];this.l[0]=128;for(var a=1;a<this.i;++a)this.l[a]=0;this.o=this.j=0;this.reset()}
F(sd,rd);sd.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.j=0};
function td(a,b,c){c||(c=0);var d=a.u;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
sd.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.i,d=0,e=this.m,f=this.j;d<b;){if(0==f)for(;d<=c;)td(this,a,d),d+=this.i;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.i){td(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.i){td(this,e);f=0;break}}this.j=f;this.o+=b}};
sd.prototype.digest=function(){var a=[],b=8*this.o;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.i-(this.j-56));for(var c=this.i-1;56<=c;c--)this.m[c]=b&255,b/=256;td(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function ud(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=vd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,wd[c])c=wd[c];else{c=String(c);if(!wd[c]){var f=/function\s+([^\(]+)/m.exec(c);wd[c]=f?f[1]:"[Anonymous]"}c=wd[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function vd(a,b){b||(b={});b[xd(a)]=!0;var c=a.stack||"";(a=a.xk)&&!b[xd(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=vd(a,b));return c}
function xd(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var wd={};function yd(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function zd(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];La(d)?zd.apply(null,d):yd(d)}}
;function L(){this.h=this.h;this.o=this.o}
L.prototype.h=!1;L.prototype.dispose=function(){this.h||(this.h=!0,this.B())};
function Ad(a,b){a.h?b():(a.o||(a.o=[]),a.o.push(b))}
L.prototype.B=function(){if(this.o)for(;this.o.length;)this.o.shift()()};function Bd(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Cd(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Dd(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Bd(a).match(/\S+/g)||[],b=0<=Ya(a,b));return b}
function Ed(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Dd(a,"inverted-hdpi")&&Cd(a,Za(a.classList?a.classList:Bd(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var Fd="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function Gd(){}
Gd.prototype.next=function(){throw Fd;};
Gd.prototype.L=function(){return this};
function Hd(a){if(a instanceof Gd)return a;if("function"==typeof a.L)return a.L(!1);if(La(a)){var b=0,c=new Gd;c.next=function(){for(;;){if(b>=a.length)throw Fd;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function Id(a,b){if(La(a))try{G(a,b,void 0)}catch(c){if(c!==Fd)throw c;}else{a=Hd(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==Fd)throw c;}}}
function Jd(a){if(La(a))return db(a);a=Hd(a);var b=[];Id(a,function(c){b.push(c)});
return b}
;function Kd(a,b){this.i={};this.h=[];this.N=this.j=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Kd)for(c=Ld(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Ld(a){Md(a);return a.h.concat()}
m=Kd.prototype;m.equals=function(a,b){if(this===a)return!0;if(this.j!=a.j)return!1;b=b||Nd;Md(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Nd(a,b){return a===b}
m.isEmpty=function(){return 0==this.j};
m.clear=function(){this.i={};this.N=this.j=this.h.length=0};
m.remove=function(a){return Object.prototype.hasOwnProperty.call(this.i,a)?(delete this.i[a],this.j--,this.N++,this.h.length>2*this.j&&Md(this),!0):!1};
function Md(a){if(a.j!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Object.prototype.hasOwnProperty.call(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.j!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Object.prototype.hasOwnProperty.call(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return Object.prototype.hasOwnProperty.call(this.i,a)?this.i[a]:b};
m.set=function(a,b){Object.prototype.hasOwnProperty.call(this.i,a)||(this.j++,this.h.push(a),this.N++);this.i[a]=b};
m.forEach=function(a,b){for(var c=Ld(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new Kd(this)};
m.L=function(a){Md(this);var b=0,c=this.N,d=this,e=new Gd;e.next=function(){if(c!=d.N)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw Fd;var f=d.h[b++];return a?f:d.i[f]};
return e};var Od=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",Ia,b),y.removeEventListener("test",Ia,b)}catch(c){}return a}();function Pd(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Pd.prototype.stopPropagation=function(){this.j=!0};
Pd.prototype.preventDefault=function(){this.defaultPrevented=!0};function Qd(a,b){Pd.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
F(Qd,Pd);var Rd={2:"touch",3:"pen",4:"mouse"};
Qd.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(hc){a:{try{dc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Rd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Qd.H.preventDefault.call(this)};
Qd.prototype.stopPropagation=function(){Qd.H.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Qd.prototype.preventDefault=function(){Qd.H.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Sd="closure_listenable_"+(1E6*Math.random()|0);var Td=0;function Ud(a,b,c,d,e){this.listener=a;this.h=null;this.src=b;this.type=c;this.capture=!!d;this.da=e;this.key=++Td;this.Y=this.ba=!1}
function Vd(a){a.Y=!0;a.listener=null;a.h=null;a.src=null;a.da=null}
;function Wd(a){this.src=a;this.listeners={};this.h=0}
Wd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Xd(a,b,d,e);-1<g?(b=a[g],c||(b.ba=!1)):(b=new Ud(b,this.src,f,!!d,e),b.ba=c,a.push(b));return b};
Wd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Xd(e,b,c,d);return-1<b?(Vd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Yd(a,b){var c=b.type;c in a.listeners&&cb(a.listeners[c],b)&&(Vd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Xd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Y&&f.listener==b&&f.capture==!!c&&f.da==d)return e}return-1}
;var Zd="closure_lm_"+(1E6*Math.random()|0),$d={},ae=0;function be(a,b,c,d,e){if(d&&d.once)ce(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)be(a,b[f],c,d,e);else c=de(c),a&&a[Sd]?ee(a,b,c,C(d)?!!d.capture:!!d,e):fe(a,b,c,!1,d,e)}
function fe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=C(e)?!!e.capture:!!e,h=ge(a);h||(a[Zd]=h=new Wd(a));c=h.add(b,c,d,g,f);if(!c.h){d=he();c.h=d;d.src=a;d.listener=c;if(a.addEventListener)Od||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ie(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ae++}}
function he(){function a(c){return b.call(a.src,a.listener,c)}
var b=je;return a}
function ce(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ce(a,b[f],c,d,e);else c=de(c),a&&a[Sd]?a.i.add(String(b),c,!0,C(d)?!!d.capture:!!d,e):fe(a,b,c,!0,d,e)}
function ke(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ke(a,b[f],c,d,e);else(d=C(d)?!!d.capture:!!d,c=de(c),a&&a[Sd])?a.i.remove(String(b),c,d,e):a&&(a=ge(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Xd(b,c,d,e)),(c=-1<a?b[a]:null)&&le(c))}
function le(a){if("number"!==typeof a&&a&&!a.Y){var b=a.src;if(b&&b[Sd])Yd(b.i,a);else{var c=a.type,d=a.h;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ie(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ae--;(c=ge(b))?(Yd(c,a),0==c.h&&(c.src=null,b[Zd]=null)):Vd(a)}}}
function ie(a){return a in $d?$d[a]:$d[a]="on"+a}
function je(a,b){if(a.Y)a=!0;else{b=new Qd(b,this);var c=a.listener,d=a.da||a.src;a.ba&&le(a);a=c.call(d,b)}return a}
function ge(a){a=a[Zd];return a instanceof Wd?a:null}
var me="__closure_events_fn_"+(1E9*Math.random()>>>0);function de(a){if("function"===typeof a)return a;a[me]||(a[me]=function(b){return a.handleEvent(b)});
return a[me]}
;function ne(){L.call(this);this.i=new Wd(this);this.F=this;this.u=null}
F(ne,L);ne.prototype[Sd]=!0;ne.prototype.addEventListener=function(a,b,c,d){be(this,a,b,c,d)};
ne.prototype.removeEventListener=function(a,b,c,d){ke(this,a,b,c,d)};
function oe(a,b){var c=a.u;if(c){var d=[];for(var e=1;c;c=c.u)d.push(c),++e}a=a.F;c=b.type||b;"string"===typeof b?b=new Pd(b,a):b instanceof Pd?b.target=b.target||a:(e=b,b=new Pd(c,a),pb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=pe(g,c,!0,b)&&e}b.j||(g=b.h=a,e=pe(g,c,!0,b)&&e,b.j||(e=pe(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=pe(g,c,!1,b)&&e}
ne.prototype.B=function(){ne.H.B.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Vd(d[e]);delete a.listeners[c];a.h--}}this.u=null};
function ee(a,b,c,d,e){a.i.add(String(b),c,!1,d,e)}
function pe(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Y&&g.capture==c){var h=g.listener,k=g.da||g.src;g.ba&&Yd(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function qe(a){var b=[];re(new se,a,b);return b.join("")}
function se(){}
function re(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),re(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),te(d,c),c.push(":"),re(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":te(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var ue={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},ve=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function te(a,b){b.push('"',a.replace(ve,function(c){var d=ue[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),ue[c]=d);return d}),'"')}
;function we(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function M(a){this.h=0;this.u=void 0;this.l=this.i=this.j=null;this.o=this.m=!1;if(a!=Ia)try{var b=this;a.call(void 0,function(c){xe(b,2,c)},function(c){xe(b,3,c)})}catch(c){xe(this,3,c)}}
function ye(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
ye.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var ze=new dd(function(){return new ye},function(a){a.reset()});
function Ae(a,b,c){var d=ze.get();d.i=a;d.onRejected=b;d.context=c;return d}
function Be(a){return new M(function(b,c){c(a)})}
M.prototype.then=function(a,b,c){return Ce(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
M.prototype.$goog_Thenable=!0;function De(a,b){return Ce(a,null,b,void 0)}
M.prototype.cancel=function(a){if(0==this.h){var b=new Ee(a);ld(function(){Fe(this,b)},this)}};
function Fe(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Fe(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Ge(c),He(c,e,3,b)))}a.j=null}else xe(a,3,b)}
function Ie(a,b){a.i||2!=a.h&&3!=a.h||Je(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Ce(a,b,c,d){var e=Ae(null,null,null);e.h=new M(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Ee?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Ie(a,e);return e.h}
M.prototype.C=function(a){this.h=0;xe(this,2,a)};
M.prototype.F=function(a){this.h=0;xe(this,3,a)};
function xe(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.F;if(d instanceof M){Ie(d,Ae(e||Ia,f||null,a));var g=!0}else if(we(d))d.then(e,f,a),g=!0;else{if(C(d))try{var h=d.then;if("function"===typeof h){Ke(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.u=c,a.h=b,a.j=null,Je(a),3!=b||c instanceof Ee||Le(a,c))}}
function Ke(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Je(a){a.m||(a.m=!0,ld(a.A,a))}
function Ge(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
M.prototype.A=function(){for(var a;a=Ge(this);)He(this,a,this.h,this.u);this.m=!1};
function He(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.o;a=a.j)a.o=!1;if(b.h)b.h.j=null,Me(b,c,d);else try{b.j?b.i.call(b.context):Me(b,c,d)}catch(e){Ne.call(null,e)}ed(ze,b)}
function Me(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Le(a,b){a.o=!0;ld(function(){a.o&&Ne.call(null,b)})}
var Ne=hd;function Ee(a){Va.call(this,a)}
F(Ee,Va);Ee.prototype.name="cancel";function N(a){L.call(this);this.u=1;this.l=[];this.m=0;this.i=[];this.j={};this.A=!!a}
F(N,L);m=N.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.u;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.u=e+3;d.push(e);return e};
function Oe(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=bb(b,function(f){return e[f+1]==c&&e[f+2]==d}))&&a.X(b)}}
m.X=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ia):(c&&cb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.O=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];Pe(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.X(c)}}return 0!=e}return!1};
function Pe(a,b,c){ld(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(G(b,this.X,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.B=function(){N.H.B.call(this);this.clear();this.l.length=0};function Qe(a){this.h=a}
Qe.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,qe(b))};
Qe.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Qe.prototype.remove=function(a){this.h.remove(a)};function Re(a){this.h=a}
F(Re,Qe);function Se(a){this.data=a}
function Te(a){return void 0===a||a instanceof Se?a:new Se(a)}
Re.prototype.set=function(a,b){Re.H.set.call(this,a,Te(b))};
Re.prototype.i=function(a){a=Re.H.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Re.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Ue(a){this.h=a}
F(Ue,Re);Ue.prototype.set=function(a,b,c){if(b=Te(b)){if(c){if(c<Date.now()){Ue.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Ue.H.set.call(this,a,b)};
Ue.prototype.i=function(a){var b=Ue.H.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Ue.prototype.remove.call(this,a);else return b}};function Ve(){}
;function We(){}
F(We,Ve);We.prototype.clear=function(){var a=Jd(this.L(!0)),b=this;G(a,function(c){b.remove(c)})};function Xe(a){this.h=a}
F(Xe,We);m=Xe.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.L=function(a){var b=0,c=this.h,d=new Gd;d.next=function(){if(b>=c.length)throw Fd;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Ye(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
F(Ye,Xe);function Ze(a,b){this.i=a;this.h=null;if(fc&&!(9<=Number(rc))){$e||($e=new Kd);this.h=$e.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),$e.set(a,this.h));try{this.h.load(this.i)}catch(c){this.h=null}}}
F(Ze,We);var af={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},$e=null;function bf(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return af[b]})}
m=Ze.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(bf(a),b);cf(this)};
m.get=function(a){a=this.h.getAttribute(bf(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(bf(a));cf(this)};
m.L=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Gd;d.next=function(){if(b>=c.length)throw Fd;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);cf(this)};
function cf(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function df(a,b){this.i=a;this.h=b+"::"}
F(df,We);df.prototype.set=function(a,b){this.i.set(this.h+a,b)};
df.prototype.get=function(a){return this.i.get(this.h+a)};
df.prototype.remove=function(a){this.i.remove(this.h+a)};
df.prototype.L=function(a){var b=this.i.L(!0),c=this,d=new Gd;d.next=function(){for(var e=b.next();e.substr(0,c.h.length)!=c.h;)e=b.next();return a?e.substr(c.h.length):c.i.get(e)};
return d};function ef(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var ff=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};A("yt.config_",ff,void 0);function O(a){ef(ff,arguments)}
function H(a,b){return a in ff?ff[a]:b}
;var gf=[];function hf(a){gf.forEach(function(b){return b(a)})}
function jf(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){kf(b),hf(b)}}:a}
function kf(a){var b=B("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0):(b=H("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0]),O("ERRORS",b))}
function lf(a){var b=B("yt.logging.errors.log");b?b(a,"WARNING",void 0,void 0,void 0):(b=H("ERRORS",[]),b.push([a,"WARNING",void 0,void 0,void 0]),O("ERRORS",b))}
;var mf=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",mf,void 0);function nf(a){ef(mf,arguments)}
;function Q(a){a=of(a);return"string"===typeof a&&"false"===a?!1:!!a}
function pf(a,b){a=of(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function of(a){var b=H("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:H("EXPERIMENT_FLAGS",{})[a]}
;var qf=0;A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++qf},void 0);var rf={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function sf(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in rf||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function tf(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
sf.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
sf.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
sf.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var hb=y.ytEventsEventsListeners||{};A("ytEventsEventsListeners",hb,void 0);var uf=y.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",uf,void 0);
function vf(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return gb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=C(e[4])&&C(d)&&lb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var wf=Xa(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function xf(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=vf(a,b,c,d);if(e)return e;e=++uf.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new sf(h);if(!Hc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new sf(h);
h.currentTarget=a;return c.call(a,h)};
g=jf(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),wf()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);hb[e]=[a,b,c,g,d];return e}
function yf(a){a&&("string"==typeof a&&(a=[a]),G(a,function(b){if(b in hb){var c=hb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?wf()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete hb[b]}}))}
;var zf=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function R(a,b){"function"===typeof a&&(a=jf(a));return window.setTimeout(a,b)}
function Af(a){window.clearTimeout(a)}
;function Bf(a){this.C=a;this.i=null;this.m=0;this.A=null;this.u=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.I=xf(window,"mousemove",E(this.J,this));a=E(this.F,this);"function"===typeof a&&(a=jf(a));this.K=window.setInterval(a,25)}
F(Bf,L);Bf.prototype.J=function(a){void 0===a.h&&tf(a);var b=a.h;void 0===a.i&&tf(a);this.i=new zc(b,a.i)};
Bf.prototype.F=function(){if(this.i){var a=zf();if(0!=this.m){var b=this.A,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.u)/this.u)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.C();this.u=d}this.m=a;this.A=this.i;this.l=(this.l+1)%4}};
Bf.prototype.B=function(){window.clearInterval(this.K);yf(this.I)};function Cf(){}
function Df(a,b){return Ef(a,1,b)}
function Ff(a,b){Ef(a,2,b)}
;function Gf(){Cf.apply(this,arguments)}
v(Gf,Cf);function Ef(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):R(a,c||0)}
function Hf(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):Af(a)}}
Gf.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Gf.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};
Ja(Gf);Gf.getInstance();var If={};
function Jf(a){var b=void 0===a?{}:a;a=void 0===b.Ha?!0:b.Ha;b=void 0===b.Ua?!1:b.Ua;if(null==B("_lact",window)){var c=parseInt(H("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Kf();xf(document,"keydown",Kf);xf(document,"keyup",Kf);xf(document,"mousedown",Kf);xf(document,"mouseup",Kf);a&&(b?xf(window,"touchmove",function(){Lf("touchmove",200)},{passive:!0}):(xf(window,"resize",function(){Lf("resize",200)}),xf(window,"scroll",function(){Lf("scroll",200)})));
new Bf(function(){Lf("mouse",100)});
xf(document,"touchstart",Kf,{passive:!0});xf(document,"touchend",Kf,{passive:!0})}}
function Lf(a,b){If[a]||(If[a]=!0,Df(function(){Kf();If[a]=!1},b))}
function Kf(){null==B("_lact",window)&&Jf();var a=Date.now();A("_lact",a,window);-1==B("_fact",window)&&A("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function Mf(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function Nf(){var a=Of;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a,void 0)}
function Pf(a){A("yt.ads.biscotti.lastId_",a,void 0)}
;var Qf=/^[\w.]*$/,Rf={q:!0,search_query:!0};function Sf(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Tf(f[0]||""),h=Tf(f[1]||"");g in c?Array.isArray(c[g])?eb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(n){var k=n,l=f[0],p=String(Sf);k.args=[{key:l,value:f[1],query:a,method:Uf==p?"unchanged":p}];Rf.hasOwnProperty(l)||lf(k)}}return c}
var Uf=String(Sf);function Vf(a){var b=[];fb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];G(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Wf(a){"?"==a.charAt(0)&&(a=a.substr(1));return Sf(a,"&")}
function Xf(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Wf(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return $b(a,e)+d}
function Yf(a){if(!b)var b=window.location.href;var c=a.match(Vb)[1]||null,d=Xb(a);c&&d?(a=a.match(Vb),b=b.match(Vb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?Xb(b)==d&&(Number(b.match(Vb)[4]||null)||null)==(Number(a.match(Vb)[4]||null)||null):!0;return a}
function Tf(a){return a&&a.match(Qf)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Zf(a){var b=$f;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Qc;e.flash="0";a:{try{var f=b.h.top.location.href}catch(P){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?K:g;try{var h=g.history.length}catch(P){h=0}e.u_his=h;e.u_java=!!K.navigator&&"unknown"!==typeof K.navigator.javaEnabled&&!!K.navigator.javaEnabled&&K.navigator.javaEnabled();K.screen&&(e.u_h=K.screen.height,e.u_w=K.screen.width,
e.u_ah=K.screen.availHeight,e.u_aw=K.screen.availWidth,e.u_cd=K.screen.colorDepth);K.navigator&&K.navigator.plugins&&(e.u_nplug=K.navigator.plugins.length);K.navigator&&K.navigator.mimeTypes&&(e.u_nmime=K.navigator.mimeTypes.length);h=b.h;try{var k=h.screenX;var l=h.screenY}catch(P){}try{var p=h.outerWidth;var n=h.outerHeight}catch(P){}try{var q=h.innerWidth;var r=h.innerHeight}catch(P){}k=[h.screenLeft,h.screenTop,k,l,h.screen?h.screen.availWidth:void 0,h.screen?h.screen.availTop:void 0,p,n,q,r];
l=b.h.top;try{var w=(l||window).document,z="CSS1Compat"==w.compatMode?w.documentElement:w.body;var D=(new Ac(z.clientWidth,z.clientHeight)).round()}catch(P){D=new Ac(-12245933,-12245933)}w=D;D={};z=new bd;y.SVGElement&&y.document.createElementNS&&z.set(0);l=Mc();l["allow-top-navigation-by-user-activation"]&&z.set(1);l["allow-popups-to-escape-sandbox"]&&z.set(2);y.crypto&&y.crypto.subtle&&z.set(3);y.TextDecoder&&y.TextEncoder&&z.set(4);z=cd(z);D.bc=z;D.bih=w.height;D.biw=w.width;D.brdim=k.join();b=
b.i;b=(D.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,D.wgl=!!K.WebGLRenderingContext,D);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var $f=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return Vf(Zf(a))},void 0);var ag="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function bg(){if(!ag)return null;var a=ag();return"open"in a?a:null}
function cg(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var dg={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},
eg="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address client_dev_root_url".split(" "),fg=!1;
function gg(a,b){b=void 0===b?{}:b;var c=Yf(a),d=Q("web_ajax_ignore_global_headers_if_set"),e;for(e in dg){var f=H(dg[e]);!f||!c&&Xb(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!Xb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!Xb(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!Xb(a))b["X-YouTube-Ad-Signals"]=Vf(Zf(void 0));return b}
function hg(a){var b=window.location.search,c=Xb(a);Q("debug_handle_relative_url_for_query_forward_killswitch")||c||!Yf(a)||(c=document.location.hostname);var d=Wb(a.match(Vb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Wf(b),f={};G(eg,function(g){e[g]&&(f[g]=e[g])});
return Xf(a,f||{},!1)}
function ig(a,b){var c=b.format||"JSON";a=jg(a,b);var d=kg(a,b),e=!1,f=lg(a,function(k){if(!e){e=!0;h&&Af(h);var l=cg(k),p=null,n=400<=k.status&&500>k.status,q=500<=k.status&&600>k.status;if(l||n||q)p=mg(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(p&&p.return_code,10);break a;case "RAW":l=!0;break a}l=!!p}p=p||{};n=b.context||y;l?b.onSuccess&&b.onSuccess.call(n,k,p):b.onError&&b.onError.call(n,k,p);b.onFinish&&b.onFinish.call(n,k,p)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=R(function(){e||(e=!0,f.abort(),Af(h),g.call(b.context||y,f))},b.timeout)}return f}
function jg(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=H("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=Xf(a,b||{},!0);return a}
function kg(a,b){var c=H("XSRF_FIELD_NAME",void 0),d=H("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=H("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||Xb(a)&&!b.withCredentials&&Xb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Wf(e),pb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):Zb(e));f=e||f&&!ib(f);!fg&&f&&
"POST"!=b.method&&(fg=!0,kf(Error("AJAX request with postData should use POST")));return e}
function mg(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,lf(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?ng(a):null)e={},G(a.getElementsByTagName("*"),function(g){e[g.tagName]=og(g)})}d&&pg(e);
return e}
function pg(a){if(C(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=Qb(a[b],null);a[c]=d}else pg(a[b])}}
function ng(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function og(a){var b="";G(a.childNodes,function(c){b+=c.nodeValue});
return b}
function lg(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&jf(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=bg();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;Q("debug_forward_web_query_parameters")&&(a=hg(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=gg(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var qg=sc||tc;function rg(a){var b=Lb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var sg={},tg=0;
function ug(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!rg("cobalt")){if(a){a instanceof I||(a="object"==typeof a&&a.W?a.V():String(a),Ib.test(a)?a=new I(a,Eb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Hb))&&Gb.test(b[1])?new I(a,Eb):null));a=Fb(a||Kb);if("about:invalid#zClosurez"===a||a.startsWith("data"))a="";else{if(!(a instanceof Ob)){b="object"==typeof a;var f=null;b&&a.ka&&(f=a.ha());a=Qb(wb(b&&a.W?a.V():String(a)),f)}a instanceof Ob&&a.constructor===Ob?a=a.h:(Ka(a),a="type_error:SafeHtml");
a=encodeURIComponent(String(qe(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=Ec("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)lg(a,b,"POST",e,d);else if(H("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)lg(a,b,"GET","",d);else{b:{try{var g=new Wa({url:a});if(g.j&&g.i||g.l){var h=Wb(a.match(Vb)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(ac);d:{for(c=0;0<=(c=a.indexOf("ri",
c))&&c<l;){var p=a.charCodeAt(c-1);if(38==p||63==p){var n=a.charCodeAt(c+2);if(!n||61==n||38==n||35==n){var q=c;break d}}c+=3}q=-1}if(0>q)var r=null;else{var w=a.indexOf("&",q);if(0>w||w>l)w=l;q+=3;r=decodeURIComponent(a.substr(q,w-q).replace(/\+/g," "))}k="1"!==r}f=!k;break b}}catch(z){}f=!1}f?vg(a)?(b&&b(),f=!0):f=!1:f=!1;f||wg(a,b)}}
function xg(a){var b=void 0===b?"":b;vg(a,b)||ug(a,void 0,void 0,void 0,b)}
function vg(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function wg(a,b){var c=new Image,d=""+tg++;sg[d]=c;c.onload=c.onerror=function(){b&&sg[d]&&b();delete sg[d]};
c.src=a}
;var yg=y.ytPubsubPubsubInstance||new N,zg=y.ytPubsubPubsubSubscribedKeys||{},Ag=y.ytPubsubPubsubTopicToKeys||{},Bg=y.ytPubsubPubsubIsSynchronous||{};function Cg(a,b){var c=Dg();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){zg[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Bg[a]?f():R(f,0)}catch(g){kf(g)}},void 0);
zg[d]=!0;Ag[a]||(Ag[a]=[]);Ag[a].push(d);return d}return 0}
function Eg(a){var b=Dg();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),G(a,function(c){b.unsubscribeByKey(c);delete zg[c]}))}
function Fg(a,b){var c=Dg();c&&c.publish.apply(c,arguments)}
function Gg(a){var b=Dg();if(b)if(b.clear(a),a)Hg(a);else for(var c in Ag)Hg(c)}
function Dg(){return y.ytPubsubPubsubInstance}
function Hg(a){Ag[a]&&(a=Ag[a],G(a,function(b){zg[b]&&delete zg[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.X;N.prototype.publish=N.prototype.O;N.prototype.clear=N.prototype.clear;A("ytPubsubPubsubInstance",yg,void 0);A("ytPubsubPubsubTopicToKeys",Ag,void 0);A("ytPubsubPubsubIsSynchronous",Bg,void 0);A("ytPubsubPubsubSubscribedKeys",zg,void 0);var Ig=window,S=Ig.ytcsi&&Ig.ytcsi.now?Ig.ytcsi.now:Ig.performance&&Ig.performance.timing&&Ig.performance.now&&Ig.performance.timing.navigationStart?function(){return Ig.performance.timing.navigationStart+Ig.performance.now()}:function(){return(new Date).getTime()};var Jg=pf("initial_gel_batch_timeout",1E3),Kg=Math.pow(2,16)-1,Lg=null,Mg=0,Ng=void 0,Og=0,Pg=0,Qg=0,Rg=!0,Sg=y.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",Sg,void 0);var Tg=y.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",Tg,void 0);
function Ug(a,b){if("log_event"===a.endpoint){var c="";a.D&&(Tg[a.D.token]=Vg(a.D),c=a.D.token);var d=Sg.get(c)||[];Sg.set(c,d);d.push(a.payload);b&&(Ng=new b);a=pf("web_logging_max_batch")||100;b=S();d.length>=a?Wg({writeThenSend:!0}):10<=b-Qg&&(Xg(),Qg=b)}}
function Yg(a,b){if("log_event"===a.endpoint){var c="";a.D&&(Tg[a.D.token]=Vg(a.D),c=a.D.token);var d=new Map;d.set(c,[a.payload]);b&&(Ng=new b);return new M(function(e){Ng&&Ng.isReady()?Zg(d,e,{bypassNetworkless:!0}):e()})}}
function Wg(a){a=void 0===a?{}:a;new M(function(b){Af(Og);Af(Pg);Pg=0;Ng&&Ng.isReady()?(Zg(Sg,b,a),Sg.clear()):(Xg(),b())})}
function Xg(){Q("web_gel_timeout_cap")&&!Pg&&(Pg=R(function(){Wg({writeThenSend:!0})},6E4));
Af(Og);var a=H("LOGGING_BATCH_TIMEOUT",pf("web_gel_debounce_ms",1E4));Q("shorten_initial_gel_batch_timeout")&&Rg&&(a=Jg);Og=R(function(){Wg({writeThenSend:!0})},a)}
function Zg(a,b,c){var d=Ng;c=void 0===c?{}:c;var e=Math.round(S()),f=a.size;a=u(a);for(var g=a.next();!g.done;g=a.next()){var h=u(g.value);g=h.next().value;var k=h.next().value;h=nb({context:$g(d.h||ah())});h.events=k;(k=Tg[g])&&bh(h,g,k);delete Tg[g];ch(h,e);Q("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&xg("/generate_204");dh(d,"log_event",h,{retry:!0,onSuccess:function(){f--;f||b();Mg=Math.round(S()-e)},
onError:function(){f--;f||b()},
ya:c});Rg=!1}}
function ch(a,b){a.requestTimeMs=String(b);Q("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);if(b=H("EVENT_ID",void 0)){var c=H("BATCH_CLIENT_COUNTER",void 0)||0;c||(c=Math.floor(Math.random()*Kg/2));c++;c>Kg&&(c=1);O("BATCH_CLIENT_COUNTER",c);b={serializedEventId:b,clientCounter:String(c)};a.serializedClientEventId=b;Lg&&Mg&&Q("log_gel_rtt_web")&&(a.previousBatchInfo={serializedClientEventId:Lg,roundtripMs:String(Mg)});Lg=b;Mg=0}}
function bh(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Vg(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var eh=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",eh,void 0);function fh(a,b,c,d){d=void 0===d?{}:d;var e={};e.eventTimeMs=Math.round(d.timestamp||S());e[a]=b;a=Mf();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};Q("log_sequence_info_on_gel_web")&&d.M&&(a=e.context,b=d.M,eh[b]=b in eh?eh[b]+1:0,a.sequence={index:eh[b],groupKey:b},d.Fa&&delete eh[d.M]);(d.Fk?Yg:Ug)({endpoint:"log_event",payload:e,D:d.D},c)}
;function gh(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function hh(a,b,c,d,e){Yc.set(""+a,b,{ma:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var T=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",T,void 0);function ih(){this.h=H("ALT_PREF_COOKIE_NAME","PREF");this.i=H("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Yc.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(T[d]=c.toString())}}}
ih.prototype.get=function(a,b){jh(a);kh(a);a=void 0!==T[a]?T[a].toString():null;return null!=a?a:b?b:""};
ih.prototype.set=function(a,b){jh(a);kh(a);if(null==b)throw Error("ExpectedNotNull");T[a]=b.toString()};
ih.prototype.remove=function(a){jh(a);kh(a);delete T[a]};
ih.prototype.clear=function(){for(var a in T)delete T[a]};
function kh(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function jh(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function lh(a){a=void 0!==T[a]?T[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ja(ih);var mh={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},nh={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function oh(){var a=y.navigator;return a?a.connection:void 0}
;function ph(){return"INNERTUBE_API_KEY"in ff&&"INNERTUBE_API_VERSION"in ff}
function ah(){return{innertubeApiKey:H("INNERTUBE_API_KEY",void 0),innertubeApiVersion:H("INNERTUBE_API_VERSION",void 0),Ia:H("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ja:H("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:H("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),La:H("INNERTUBE_CONTEXT_HL",void 0),Ka:H("INNERTUBE_CONTEXT_GL",void 0),Ma:H("INNERTUBE_HOST_OVERRIDE",void 0)||"",Oa:!!H("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Na:!!H("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:H("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function $g(a){var b={client:{hl:a.La,gl:a.Ka,clientName:a.Ja,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ia}},c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=H("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=H("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=H("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});
f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!Q("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=gh()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!Q("music_web_display_mode_killswitch")){var h;b.client.xa=null!=(h=b.client.xa)?h:{};b.client.xa.webDisplayMode=gh()}a.appInstallData&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);
H("DELEGATED_SESSION_ID")&&!Q("pageid_as_header_web")&&(b.user={onBehalfOfUser:H("DELEGATED_SESSION_ID")});a:{if(h=oh()){a=mh[h.type||"unknown"]||"CONN_UNKNOWN";h=mh[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);Q("web_log_effective_connection_type")&&(a=oh(),a=null!==a&&void 0!==a&&a.effectiveType?nh.hasOwnProperty(a.effectiveType)?nh[a.effectiveType]:
"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(Wf(H("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function qh(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||H("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.vk||H("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().uk:b=ad([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=H("SESSION_INDEX",0),Q("pageid_as_header_web")&&(d["X-Goog-PageId"]=H("DELEGATED_SESSION_ID")));return d}
;function rh(a){a=Object.assign({},a);delete a.Authorization;var b=ad();if(b){var c=new sd;c.update(H("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=xc(c.digest())}return a}
;function sh(a){var b=new Ye;(b=b.isAvailable()?a?new df(b,a):b:null)||(a=new Ze(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Ue(a):null;this.i=document.domain||window.location.hostname}
sh.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(qe(b))}catch(f){return}else e=escape(b);hh(a,e,c,this.i)};
sh.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Yc.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
sh.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Yc.remove(""+a,"/",void 0===b?"youtube.com":b)};var th;function uh(){th||(th=new sh("yt.innertube"));return th}
function vh(a,b,c,d){if(d)return null;d=uh().get("nextId",!0)||1;var e=uh().get("requests",!0)||{};e[d]={method:a,request:b,authState:rh(c),requestTime:Math.round(S())};uh().set("nextId",d+1,86400,!0);uh().set("requests",e,86400,!0);return d}
function wh(a){var b=uh().get("requests",!0)||{};delete b[a];uh().set("requests",b,86400,!0)}
function xh(a){var b=uh().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(S())-d.requestTime)){var e=d.authState,f=rh(qh(!1));lb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(S())),dh(a,d.method,e,{}));delete b[c]}}uh().set("requests",b,86400,!0)}}
;function yh(a,b){this.version=a;this.args=b}
;function zh(a,b){this.topic=a;this.h=b}
zh.prototype.toString=function(){return this.topic};var Ah=B("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.X;N.prototype.publish=N.prototype.O;N.prototype.clear=N.prototype.clear;A("ytPubsub2Pubsub2Instance",Ah,void 0);var Bh=B("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",Bh,void 0);var Ch=B("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",Ch,void 0);var Dh=B("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",Dh,void 0);
A("ytPubsub2Pubsub2SkipSubKey",null,void 0);function Eh(a,b){var c=Fh();c&&c.publish.call(c,a.toString(),a,b)}
function Gh(a){var b=Hh,c=Fh();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Bh[d])try{if(f&&b instanceof zh&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.N){var l=new h;h.N=l.version}var p=h.N}catch(n){}if(!p||k.version!=p)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
db(k.args))}catch(n){throw n.message="yt.pubsub2.Data.deserialize(): "+n.message,n;}}catch(n){throw n.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+n.message,n;}a.call(window,f)}catch(n){kf(n)}},Dh[b.toString()]?B("yt.scheduler.instance")?Df(g):R(g,0):g())});
Bh[d]=!0;Ch[b.toString()]||(Ch[b.toString()]=[]);Ch[b.toString()].push(d);return d}
function Ih(){var a=Jh,b=Gh(function(c){a.apply(void 0,arguments);Kh(b)});
return b}
function Kh(a){var b=Fh();b&&("number"===typeof a&&(a=[a]),G(a,function(c){b.unsubscribeByKey(c);delete Bh[c]}))}
function Fh(){return B("ytPubsub2Pubsub2Instance")}
;var Lh=[],Mh=!1;function Nh(a,b){Mh||(Lh.push({type:"EVENT",eventType:a,payload:b}),10<Lh.length&&Lh.shift())}
;var Oh=function(){var a;return function(){a||(a=new sh("ytidb"));return a}}();
function Ph(a,b,c){var d;this.i=void 0===a?!1:a;this.failureMessage=b;this.j=c;this.h=null===(d=Oh())||void 0===d?void 0:d.get("LAST_RESULT_ENTRY_KEY",!0);this.h||(this.h={createdTimestampMs:S(),isSupported:this.i,resultCount:0});var e;if(Qh()){var f;this.h.isSupported===this.i?f=Object.assign(Object.assign({},this.h),{resultCount:this.h.resultCount+1}):f={isSupported:this.i,resultCount:1,createdTimestampMs:S()};null===(e=Oh())||void 0===e?void 0:e.set("LAST_RESULT_ENTRY_KEY",f,2592E3,!0)}}
function Rh(a,b){return new Ph(!1,a instanceof Error?a.message:"",void 0===b?!1:b)}
Ph.prototype.isSupported=function(){return this.i};
Ph.prototype.log=function(){Qh()&&Nh("IS_SUPPORTED_COMPLETED",{isSupported:this.i,lastIsSupported:this.h.isSupported,failureMessage:this.failureMessage,sameResultCount:this.h.resultCount,sameResultDurationMs:Math.floor(S()-this.h.createdTimestampMs),canDetectDataOnFailure:this.j})};
function Qh(){var a;return!!(Q("ytidb_analyze_is_supported")&&(null===(a=Oh())||void 0===a?0:a.h))}
;function U(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(c instanceof Array?c:fa(u(c)))}
v(U,Error);function Sh(a){return a.substr(0,a.indexOf(":"))||a}
;var Th={},Uh=(Th.AUTH_INVALID="No user identifier specified.",Th.EXPLICIT_ABORT="Transaction was explicitly aborted.",Th.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Th.MISSING_OBJECT_STORE="Object store not created.",Th.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Th.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Th.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Th.EXECUTE_TRANSACTION_ON_CLOSED_DB=
"Can't start a transaction on a closed database",Th),Vh={},Wh=(Vh.AUTH_INVALID="ERROR",Vh.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Vh.EXPLICIT_ABORT="IGNORED",Vh.IDB_NOT_SUPPORTED="ERROR",Vh.MISSING_OBJECT_STORE="ERROR",Vh.QUOTA_EXCEEDED="WARNING",Vh.QUOTA_MAYBE_EXCEEDED="WARNING",Vh.UNKNOWN_ABORT="WARNING",Vh),Xh={},Yh=(Xh.AUTH_INVALID=!1,Xh.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Xh.EXPLICIT_ABORT=!1,Xh.IDB_NOT_SUPPORTED=!1,Xh.MISSING_OBJECT_STORE=!1,Xh.QUOTA_EXCEEDED=!1,Xh.QUOTA_MAYBE_EXCEEDED=!0,
Xh.UNKNOWN_ABORT=!0,Xh);function V(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Uh[a]:c;d=void 0===d?Wh[a]:d;e=void 0===e?Yh[a]:e;U.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,V.prototype)}
v(V,U);function Zh(a){V.call(this,"MISSING_OBJECT_STORE",{Ak:a},Uh.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,Zh.prototype)}
v(Zh,V);var $h=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function ai(a,b,c){b=Sh(b);var d=a instanceof Error?a:Error("Unexpected error: "+a);if(d instanceof V)return d;if("QuotaExceededError"===d.name)return new V("QUOTA_EXCEEDED",{objectStoreNames:c,dbName:b});if(uc&&"UnknownError"===d.name)return new V("QUOTA_MAYBE_EXCEEDED",{objectStoreNames:c,dbName:b});if("InvalidStateError"===d.name&&$h.some(function(e){return d.message.includes(e)}))return new V("EXECUTE_TRANSACTION_ON_CLOSED_DB",{objectStoreNames:c,
dbName:b});if("AbortError"===d.name)return new V("UNKNOWN_ABORT",{objectStoreNames:c,dbName:b},d.message);d.args=[{name:"IdbError",Bk:d.name,dbName:b,objectStoreNames:c}];d.level="WARNING";return d}
;function bi(a){if(!a)throw Error();throw a;}
function ci(a){return a}
function W(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.i=a;this.state={status:"PENDING"};this.h=[];this.onRejected=[];try{this.i(c,b)}catch(e){b(e)}}
W.all=function(a){return new W(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={R:0};f.R<a.length;f={R:f.R},++f.R)di(W.resolve(a[f.R]).then(function(g){return function(h){d[g.R]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})})};
W.resolve=function(a){return new W(function(b,c){a instanceof W?a.then(b,c):b(a)})};
W.reject=function(a){return new W(function(b,c){c(a)})};
W.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:ci,e=null!==b&&void 0!==b?b:bi;return new W(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){ei(c,c,d,f,g)}),c.onRejected.push(function(){fi(c,c,e,f,g)})):"FULFILLED"===c.state.status?ei(c,c,d,f,g):"REJECTED"===c.state.status&&fi(c,c,e,f,g)})};
function di(a,b){a.then(void 0,b)}
function ei(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof W?gi(a,b,f,d,e):d(f)}catch(g){e(g)}}
function fi(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof W?gi(a,b,f,d,e):d(f)}catch(g){e(g)}}
function gi(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof W?gi(a,b,f,d,e):d(f)},function(f){e(f)})}
;function hi(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function ii(a){return new Promise(function(b,c){hi(a,b,c)})}
function X(a){return new W(function(b,c){hi(a,b,c)})}
;function ji(a,b){return new W(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()})}
;function ki(a){return new Promise(function(b){Ff(function(){b()},a)})}
function li(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(S());this.i=!1}
m=li.prototype;m.add=function(a,b,c){return mi(this,[a],{mode:"readwrite",U:Q("ytidb_transaction_enable_retries_core_and_nwl")},function(d){return ni(d,a).add(b,c)})};
m.clear=function(a){return mi(this,[a],{mode:"readwrite",U:Q("ytidb_transaction_enable_retries_core_and_nwl")},function(b){return ni(b,a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return mi(this,[a],{mode:"readonly",U:Q("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return ni(c,a).count(b)})};
m.delete=function(a,b){return mi(this,[a],{mode:"readwrite",U:Q("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return ni(c,a).delete(b)})};
m.get=function(a,b){return mi(this,[a],{mode:"readonly",U:Q("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return ni(c,a).get(b)})};
function mi(a,b,c,d){return bc(a,function f(){var g=this,h,k,l,p,n,q,r,w,z,D,P,ia,la,ll;return za(f,function(Z){switch(Z.h){case 1:var Ua={mode:"readonly",U:!1};"string"===typeof c?Ua.mode=c:Ua=c;h=Ua;g.transactionCount++;k=Q("ytidb_transaction_exponential_backoff_retries");l=h.U?pf("ytidb_transaction_try_count",1):1;p=500;n=0;case 2:if(q){Z.h=3;break}n++;r=Math.round(S());Z.j=4;w=g.h.transaction(b,h.mode);Ua=new oi(w);Ua=pi(Ua,d);return x(Z,Ua,6);case 6:return z=Z.i,D=Math.round(S()),qi(g,r,D,n,
void 0,b.join(),h),Z.return(z);case 4:P=ta(Z);ia=Math.round(S());la=ai(P,g.h.name,b.join());if((ll=la instanceof V&&!la.h)||n>=l){qi(g,r,ia,n,la,b.join(),h);q=la;Z.h=2;break}if(!k){Z.h=2;break}return x(Z,ki(p),9);case 9:p*=2;Z.h=2;break;case 3:return Z.return(Promise.reject(q))}})})}
function qi(a,b,c,d,e,f,g){b=c-b;e?(e instanceof V&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Nh("QUOTA_EXCEEDED",{dbName:Sh(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof V&&"UNKNOWN_ABORT"===e.type&&(Nh("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c-a.j}),a.i=!0),ri(a,!1,d,f,b),Mh||(Lh.push({type:"ERROR",payload:e}),10<Lh.length&&Lh.shift())):
ri(a,!0,d,f,b)}
function ri(a,b,c,d,e){Nh("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c})}
function si(a){this.h=a}
m=si.prototype;m.add=function(a,b){return X(this.h.add(a,b))};
m.clear=function(){return X(this.h.clear()).then(function(){})};
m.count=function(a){return X(this.h.count(a))};
function ti(a,b){return ui(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?ti(this,a):X(this.h.delete(a))};
m.get=function(a){return X(this.h.get(a))};
m.index=function(a){return new vi(this.h.index(a))};
m.getName=function(){return this.h.name};
function ui(a,b,c){a=a.h.openCursor(b.query,b.direction);return wi(a).then(function(d){return ji(d,c)})}
function oi(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=V;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function pi(a,b){var c=new Promise(function(d,e){di(b(a).then(function(f){a.commit();d(f)}),e)});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
oi.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new V("EXPLICIT_ABORT");};
oi.prototype.commit=function(){var a=this.h;a.commit&&!this.aborted&&a.commit()};
function ni(a,b){b=a.h.objectStore(b);var c=a.i.get(b);c||(c=new si(b),a.i.set(b,c));return c}
function vi(a){this.h=a}
vi.prototype.count=function(a){return X(this.h.count(a))};
vi.prototype.delete=function(a){return xi(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
vi.prototype.get=function(a){return X(this.h.get(a))};
vi.prototype.getKey=function(a){return X(this.h.getKey(a))};
function xi(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return wi(a).then(function(d){return ji(d,c)})}
function yi(a,b){this.request=a;this.cursor=b}
function wi(a){return X(a).then(function(b){return null===b?null:new yi(a,b)})}
m=yi.prototype;m.advance=function(a){this.cursor.advance(a);return wi(this.request)};
m.continue=function(a){this.cursor.continue(a);return wi(this.request)};
m.delete=function(){return X(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return X(this.cursor.update(a))};function zi(a,b,c){return bc(this,function e(){var f,g,h,k,l,p,n,q,r,w;return za(e,function(z){if(1==z.h)return f=self.indexedDB.open(a,b),g=c,h=g.blocked,k=g.blocking,l=g.fb,p=g.upgrade,n=g.closed,r=function(){q||(q=new li(f.result,{closed:n}));return q},f.addEventListener("upgradeneeded",function(D){if(null===D.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");
if(null===f.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");D.dataLoss&&"none"!==D.dataLoss&&Nh("IDB_DATA_CORRUPTED",{reason:D.dataLossMessage||"unknown reason",dbName:Sh(a)});var P=r(),ia=new oi(f.transaction);p&&p(P,D.oldVersion,D.newVersion,ia)}),h&&f.addEventListener("blocked",function(){h()}),x(z,ii(f),2);
w=z.i;k&&w.addEventListener("versionchange",function(){k(r())});
w.addEventListener("close",function(){Nh("IDB_UNEXPECTEDLY_CLOSED",{dbName:Sh(a),dbVersion:w.version});l&&l()});
return z.return(r())})})}
function Ai(a,b){b=void 0===b?{}:b;return bc(this,function d(){var e,f,g;return za(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return x(h,ii(e),0)})})}
;function Bi(a){this.name="YtIdbMeta";this.options=a;this.i=!1}
function Ci(a,b,c){c=void 0===c?{}:c;c=void 0===c?{}:c;return zi(a,b,c)}
Bi.prototype.delete=function(a){a=void 0===a?{}:a;return Ai(this.name,a)};
Bi.prototype.open=function(){var a=this;if(!this.h){var b,c=function(){a.h===b&&(a.h=void 0)},d={blocking:function(f){f.close()},
closed:c,fb:c,upgrade:this.options.upgrade},e=function(){return bc(a,function g(){var h=this,k,l,p;return za(g,function(n){switch(n.h){case 1:return n.j=2,x(n,Ci(h.name,h.options.version,d),4);case 4:k=n.i;a:{var q=u(Object.keys(h.options.Ra));for(var r=q.next();!r.done;r=q.next())if(r=r.value,!k.h.objectStoreNames.contains(r)){q=r;break a}q=void 0}l=q;if(void 0===l){n.h=5;break}if(h.i){n.h=6;break}h.i=!0;return x(n,h.delete(),7);case 7:return n.return(e());case 6:throw new Zh(l);case 5:return n.return(k);
case 2:p=ta(n);if(p instanceof DOMException?"VersionError"===p.name:"DOMError"in self&&p instanceof DOMError?"VersionError"===p.name:p instanceof Object&&"message"in p&&"An attempt was made to open a database using a lower version than the existing version."===p.message)return n.return(Ci(h.name,void 0,Object.assign(Object.assign({},d),{upgrade:void 0})));c();throw p;}})})};
this.h=b=e()}return this.h};var Di=new Bi({Ra:{databases:!0},upgrade:function(a,b){1>b&&a.h.createObjectStore("databases",{keyPath:"actualName"})}});
function Ei(a){return bc(this,function c(){var d;return za(c,function(e){if(1==e.h)return x(e,Di.open(),2);d=e.i;return e.return(mi(d,["databases"],"readwrite",function(f){var g=ni(f,"databases");return g.get(a.actualName).then(function(h){if(h?a.actualName!==h.actualName||a.publicName!==h.publicName||a.userIdentifier!==h.userIdentifier||a.clearDataOnAuthChange!==h.clearDataOnAuthChange:1)return X(g.h.put(a,void 0)).then(function(){})})}))})})}
function Fi(){return bc(this,function b(){var c;return za(b,function(d){if(1==d.h)return x(d,Di.open(),2);c=d.i;return d.return(c.delete("databases","yt-idb-test-do-not-use"))})})}
function Gi(){return bc(this,function b(){var c,d;return za(b,function(e){if(1==e.h)return x(e,Di.open(),2);if(3!=e.h)return c=e.i,x(e,c.count("databases"),3);d=e.i;return e.return(0<d)})})}
;var Hi;
function Ii(){return bc(this,function b(){var c,d,e,f;return za(b,function(g){switch(g.h){case 1:var h;if(h=qg)h=/WebKit\/([0-9]+)/.exec(Lb),h=!!(h&&600<=parseInt(h[1],10));h&&(h=/WebKit\/([0-9]+)/.exec(Lb),h=!(h&&602<=parseInt(h[1],10)));if(h)return g.return(Rh(Error("YtIdb is not supported on iOS 8 or 9")));if(gc)return g.return(Rh(Error("YtIdb is not supported on Edge")));try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return g.return(Rh(Error("Non-prefixed indexedDB APIs are missing")))}catch(k){return g.return(Rh(k))}if(!("IDBTransaction"in self&&
"objectStoreNames"in IDBTransaction.prototype))return g.return(Rh(Error("IDBTransaction.prototype.objectStoreNames is missing")));g.j=2;d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return x(g,Ei(d),4);case 4:return x(g,Fi(),5);case 5:return g.return(new Ph(!0));case 2:e=ta(g);if(!Qh()){g.h=6;break}g.j=7;return x(g,Gi(),9);case 9:return f=g.i,g.return(Rh(e,f));case 7:return ta(g),g.return(Rh(e));case 6:return g.return(Rh(e))}})})}
function Ji(){if(void 0!==Hi)return Hi;Mh=!0;return Hi=Ii().then(function(a){Mh=!1;a.log();return a.isSupported()})}
;var Ki;function Li(){Ki||(Ki=new sh("yt.offline"));return Ki}
;function Mi(){ne.call(this);this.l=this.A=this.C=this.m=!1;this.j=Ni();this.l=Q("validate_network_status");Oi(this);Pi(this)}
v(Mi,ne);function Ni(){var a=window.navigator.onLine;return void 0===a?!0:a}
function Pi(a){window.addEventListener("online",function(){return bc(a,function c(){var d=this;return za(c,function(e){if(1==e.h){if(!d.l){d.j=!0;e.h=2;return}return x(e,Qi(d),3)}2!=e.h&&(d.j=e.i);d.m&&d.j&&oe(d,"ytnetworkstatus-online");Ri(d);if(d.A&&Q("offline_error_handling")){var f=Li().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new U(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;kf(h)}Li().set("errors",{},2592E3,!0)}}e.h=0})})})}
function Oi(a){window.addEventListener("offline",function(){return bc(a,function c(){var d=this;return za(c,function(e){if(1==e.h){if(!d.l){d.j=!1;e.h=2;return}return x(e,Qi(d),3)}2!=e.h&&(d.j=e.i);d.m&&!d.j&&oe(d,"ytnetworkstatus-offline");Ri(d);e.h=0})})})}
function Ri(a){a.C&&(lf(new U("NetworkStatusManager state did not match poll",S()-0)),a.C=!1)}
function Qi(a){return bc(a,function c(){var d;return za(c,function(e){switch(e.h){case 1:return e.j=2,x(e,fetch("/generate_204",{method:"HEAD"}),4);case 4:d=!0;e.h=3;e.j=0;break;case 2:ta(e),d=!1;case 3:return e.return(d)}})})}
;function Si(a){a=void 0===a?{}:a;ne.call(this);var b=this;this.l=this.A=0;Mi.h||(Mi.h=new Mi);this.j=Mi.h;this.j.m=!0;a.Qa&&(this.j.A=!0);a.ea?(this.ea=a.ea,ee(this.j,"ytnetworkstatus-online",function(){Ti(b,"publicytnetworkstatus-online")}),ee(this.j,"ytnetworkstatus-offline",function(){Ti(b,"publicytnetworkstatus-offline")})):(ee(this.j,"ytnetworkstatus-online",function(){oe(b,"publicytnetworkstatus-online")}),ee(this.j,"ytnetworkstatus-offline",function(){oe(b,"publicytnetworkstatus-offline")}))}
v(Si,ne);function Ui(){Vi||(Vi=new Si({Qa:!0}));var a=Vi.j;a.l||a.j===Ni()||lf(new U("NetworkStatusManager isOnline does not match window status"))}
function Ti(a,b){a.ea?a.l?(Hf(a.A),a.A=Df(function(){a.m!==b&&(oe(a,b),a.m=b,a.l=S())},a.ea-(S()-a.l))):(oe(a,b),a.m=b,a.l=S()):oe(a,b)}
;var Vi;function Wi(a,b){b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?Ji().then(function(){Ui();ig(a,b)}):(Ui(),ig(a,b))}
function Xi(a,b){b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?Ji().then(function(){ig(a,b)}):ig(a,b)}
;function Yi(a){var b=this;this.h=null;a?this.h=a:ph()&&(this.h=ah());Ef(function(){xh(b)},0,5E3)}
Yi.prototype.isReady=function(){!this.h&&ph()&&(this.h=ah());return!!this.h};
function dh(a,b,c,d){!H("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&lf(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var e=new U("innertube xhrclient not ready",b,c,d);kf(e);throw e;}var f={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,q){if(d.onSuccess)d.onSuccess(q)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,q){if(d.onError)d.onError(q)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0},g="";(e=a.h.Ma)&&(g=e);var h=a.h.Oa||!1,k=qh(h,g,d);Object.assign(f.headers,k);f.headers.Authorization&&!g&&(f.headers["x-origin"]=window.location.origin);e="/youtubei/"+a.h.innertubeApiVersion+"/"+b;var l={alt:"json"};a.h.Na&&f.headers.Authorization||(l.key=a.h.innertubeApiKey);var p=Xf(""+g+e,l||{},!0);(function(n){n=void 0===n?!1:n;var q;if(d.retry&&"www.youtube-nocookie.com"!=g&&(n||(q=vh(b,c,k,h)),q)){var r=f.onSuccess,w=f.onFetchSuccess;f.onSuccess=function(z,
D){wh(q);r(z,D)};
c.onFetchSuccess=function(z,D){wh(q);w(z,D)}}try{n&&d.retry&&!d.ya.bypassNetworkless?(f.method="POST",!d.ya.writeThenSend&&Q("nwl_send_fast_on_unload")?Xi(p,f):Wi(p,f)):(f.method="POST",f.postParams||(f.postParams={}),ig(p,f))}catch(z){if("InvalidAccessError"==z.name)q&&(wh(q),q=0),lf(Error("An extension is blocking network request."));
else throw z;}q&&Ef(function(){xh(a)},0,5E3)})(!1)}
;function Zi(a,b,c){c=void 0===c?{}:c;var d=Yi;H("ytLoggingEventsDefaultDisabled",!1)&&Yi==Yi&&(d=null);fh(a,b,d,c)}
;var $i=[{wa:function(a){return"Cannot read property '"+a.key+"'"},
na:{TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,
groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]}],Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}]}},{wa:function(a){return"Cannot call '"+a.key+"'"},
na:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}}];function aj(){this.h=[];this.i=[]}
var bj;function cj(){bj||(bj=new aj);return bj}
;var dj=new N;function ej(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=fj(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=fj(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=fj(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function fj(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function gj(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=hj(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f="string"!==typeof g||"clickTrackingParams"!==f&&"trackingParams"!==f?0:(g=ej(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?hj(f+".ve",g,h,k):0;d+=f;d+=hj(e,a[e],b,c);if(500<d)break}}else c[b]=ij(a),d+=c[b].length;else c[b]=ij(a),d+=c[b].length;return d}
function hj(a,b,c,d){c+="."+a;a=ij(b);d[c]=a;return c.length+a.length}
function ij(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var jj=new Set,kj=0,lj=0,mj=0,nj=[],oj=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function pj(a){qj(a,"WARNING")}
function qj(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||H("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||H("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.level&&(b=a.level),Q("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+a.fileName),
d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=kj))){var g=ud(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=gj(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var p=a.params;
if("object"===typeof a.params)for(l in p){if(p[l]){var n="params."+l,q=ij(p[l]);c[n]=q;k+=n.length+q.length;if(500<k)break}}else c.params=ij(p)}if(nj.length)for(l=0;l<nj.length&&!(k=gj(nj[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=cj();
c=u(a.i);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.zk)){a=d.weight;break a}a=u(a.h);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Da(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=u($i);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.na[l.name])for(e=u(c.na[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+e[g]]=d[g+
1];l.message=c.wa(f);break}l.params||(l.params={});a=cj();l.params["params.errorServiceSignature"]="msg="+a.i.length+"&cb="+a.h.length;l.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!jj.has(l.message)){"ERROR"===b?(dj.O("handleError",l),Q("record_app_crashed_web")&&0===mj&&1===l.sampleWeight&&
(mj++,Zi("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),lj++):"WARNING"===b&&dj.O("handleWarning",l);if(Q("kevlar_gel_error_routing")){a=b;b:{c=u(oj);for(d=c.next();!d.done;d=c.next())if(rg(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),
d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};e={pageUrl:window.location.href,kvPairs:[]};H("FEXP_EXPERIMENTS")&&(e.experimentIds=H("FEXP_EXPERIMENTS"));if(f=l.params)for(g=u(Object.keys(f)),h=g.next();!h.done;h=g.next())h=h.value,e.kvPairs.push({key:"client."+h,value:String(f[h])});
f=H("SERVER_NAME",void 0);g=H("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,logMessage:c}}c&&(Zi("clientError",c),("ERROR"===a||Q("errors_flush_gel_always_killswitch"))&&Wg())}if(!Q("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,level:b,"client.name":a.name},postParams:{url:H("PAGE_NAME",window.location.href),
file:l.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=u(Object.keys(a));for(d=c.next();!d.done;d=c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=H("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=u(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=H("SERVER_NAME",void 0);c=H("SERVER_VERSION",void 0);a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}ig(H("ECATCHER_REPORT_HOST",
"")+"/error_204",b)}jj.add(l.message);kj++}}}
function rj(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];a.args||(a.args=[]);a.args.push.apply(a.args,c instanceof Array?c:fa(u(c)))}
;function sj(a){a&&(a.dataset?a.dataset[tj("loaded")]="true":a.setAttribute("data-loaded","true"))}
function uj(a,b){return a?a.dataset?a.dataset[tj(b)]:a.getAttribute("data-"+b):null}
var vj={};function tj(a){return vj[a]||(vj[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var wj=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,xj=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function yj(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(wj,""),c=c.replace(xj,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else zj(a,b,c)}
function zj(a,b,c){c=void 0===c?null:c;var d=Aj(a),e=document.getElementById(d),f=e&&uj(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Cg(d,b),b=""+Ma(b),Bj[b]=f),g||(e=Cj(a,d,function(){uj(e,"loaded")||(sj(e),Fg(d),R(Ra(Gg,d),0))},c)))}
function Cj(a,b,c,d){d=void 0===d?null:d;var e=Fc(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Sb(e,Nc(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Dj(a){a=Aj(a);var b=document.getElementById(a);b&&(Gg(a),b.parentNode.removeChild(b))}
function Ej(a,b){a&&b&&(a=""+Ma(b),(a=Bj[a])&&Eg(a))}
function Aj(a){var b=document.createElement("a");Rb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Ub(a)}
var Bj={};var Fj=[],Gj=!1;function Hj(){if(!Q("disable_ad_status_on_html5_clients")&&(!Q("condition_ad_status_fetch_on_consent_cookie_html5_clients")||Yc.get("CONSENT","").startsWith("YES+"))&&"1"!=kb()){var a=function(){Gj=!0;"google_ad_status"in window?O("DCLKSTAT",1):O("DCLKSTAT",2)};
try{yj("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Fj.push(Df(function(){if(!(Gj||"google_ad_status"in window)){try{Ej("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Gj=!0;O("DCLKSTAT",3)}},5E3))}}
function Ij(){var a=Number(H("DCLKSTAT",0));return isNaN(a)?0:a}
;function Jj(){this.i=!1;this.h=null}
Jj.prototype.initialize=function(a,b,c,d,e,f){var g=this;f=void 0===f?!1:f;b?(this.i=!0,yj(b,function(){g.i=!1;var h=0<=b.indexOf("/th/");(h?window.trayride:window.botguard)?Kj(g,c,!!f,h,d):(Dj(b),pj(new U("Unable to load Botguard","from "+b)))},e)):a&&(e=Fc(document,"SCRIPT"),e.textContent=a,e.nonce=Ea(),document.head.appendChild(e),document.head.removeChild(e),((a=a.includes("trayride"))?window.trayride:window.botguard)?Kj(this,c,!!f,a,d):pj(Error("Unable to load Botguard from JS")))};
function Kj(a,b,c,d,e){var f,g;if(d=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{Lj(a,new d(b,e?function(){return e(b)}:Ia))}catch(h){h instanceof Error&&pj(h)}else{try{Lj(a,new d(b))}catch(h){h instanceof Error&&pj(h)}e&&e(b)}else pj(Error("Failed to finish initializing VM"))}
Jj.prototype.invoke=function(a){a=void 0===a?{}:a;return this.h?this.h.hasOwnProperty("hot")?this.h.hot(void 0,void 0,a):this.h.invoke(void 0,void 0,a):null};
Jj.prototype.dispose=function(){this.h=null};
function Lj(a,b){a.h=b}
;var Mj=new Jj;function Nj(){return!!Mj.h}
function Oj(a){a=void 0===a?{}:a;return Mj.invoke(a)}
;var Pj={Lb:29434,Nb:3611,Ce:3854,Uf:42993,Fi:4724,qj:96370,gb:27686,hb:85013,ib:23462,kb:42016,lb:62407,mb:26926,jb:43781,nb:51236,ob:79148,pb:50160,qb:77504,Cb:87907,Db:18630,Eb:54445,Fb:80935,Gb:105675,Hb:37521,Ib:47786,Jb:98349,Kb:6827,Mb:7282,Qb:32276,Pb:76278,Rb:93911,Sb:106531,Tb:27259,Ub:27262,Vb:27263,Xb:21759,Yb:27107,Zb:62936,ac:49568,cc:38408,dc:80637,ec:68727,fc:68728,hc:80353,ic:80356,jc:74610,kc:45707,lc:83962,mc:83970,nc:46713,oc:89711,pc:74612,qc:93265,sc:74611,uc:113533,wc:93252,
xc:99357,zc:94521,Ac:114252,Bc:113532,Cc:94522,yc:94583,Dc:88E3,Ec:93253,Fc:93254,Gc:94387,Hc:94388,Ic:93255,Jc:97424,tc:72502,Kc:110111,Lc:76019,Nc:117092,Oc:117093,Mc:89431,Pc:110466,Qc:77240,Rc:60508,Sc:105350,Tc:73393,Uc:113534,Vc:92098,Wc:84517,Xc:83759,Yc:80357,Zc:86113,bd:72598,cd:72733,dd:107349,ed:118203,fd:117431,gd:117429,hd:117430,jd:117432,kd:120080,ld:117259,md:121692,nd:97615,od:31402,pd:84774,qd:95117,rd:98930,sd:98931,td:98932,ud:43347,vd:45474,wd:100352,xd:84758,yd:98443,zd:117985,
Ad:74613,Bd:74614,Cd:64502,Dd:74615,Ed:74616,Fd:122224,Gd:74617,Hd:77820,Id:74618,Jd:93278,Kd:93274,Ld:93275,Md:93276,Nd:22110,Od:29433,Qd:120541,Sd:82047,Td:113550,Ud:75836,Vd:75837,Wd:42352,Xd:84512,Yd:76065,Zd:75989,ae:16623,be:32594,ce:27240,de:32633,ee:74858,he:3945,ge:16989,ie:45520,je:25488,ke:25492,le:25494,me:55760,ne:14057,oe:18451,pe:57204,qe:57203,re:17897,se:57205,te:18198,ue:17898,we:17909,xe:43980,ye:46220,ze:11721,Ae:49954,Be:96369,De:56251,Ee:25624,Fe:16906,Ge:99999,He:68172,Ie:27068,
Je:47973,Ke:72773,Le:26970,Me:26971,Ne:96805,Oe:17752,Pe:73233,Qe:109512,Re:22256,Se:14115,Te:22696,Ue:89278,Ve:89277,We:109513,Xe:43278,Ye:43459,Ze:43464,af:89279,bf:43717,cf:55764,df:22255,ef:89281,ff:40963,gf:43277,hf:43442,jf:91824,kf:120137,lf:96367,mf:36850,nf:72694,pf:37414,qf:36851,rf:121343,sf:73491,tf:54473,uf:43375,vf:46674,wf:32473,xf:72901,yf:72906,zf:50947,Af:50612,Bf:50613,Cf:50942,Df:84938,Ef:84943,Ff:84939,Gf:84941,Hf:84944,If:84940,Jf:84942,Kf:35585,Lf:51926,Mf:79983,Nf:63238,Of:18921,
Pf:63241,Qf:57893,Rf:41182,Sf:33424,Tf:22207,Vf:36229,Wf:22206,Xf:22205,Yf:18993,Zf:19001,ag:18990,cg:18991,dg:18997,eg:18725,fg:19003,gg:36874,hg:44763,jg:33427,kg:67793,lg:22182,mg:37091,ng:34650,og:50617,pg:47261,qg:22287,rg:25144,sg:97917,tg:62397,ug:36961,vg:108035,wg:27426,xg:27857,yg:27846,zg:27854,Ag:69692,Bg:61411,Cg:39299,Dg:38696,Eg:62520,Fg:36382,Gg:108701,Hg:50663,Ig:36387,Jg:14908,Kg:37533,Lg:105443,Mg:61635,Ng:62274,Og:65702,Pg:65703,Qg:65701,Rg:76256,Sg:37671,Tg:49953,Vg:36216,Wg:28237,
Xg:39553,Yg:29222,Zg:26107,ah:38050,bh:26108,eh:120745,dh:26109,fh:26110,gh:66881,hh:28236,ih:14586,jh:57929,kh:74723,lh:44098,mh:44099,nh:23528,oh:61699,ph:59149,qh:101951,rh:97346,sh:118051,uh:95102,vh:64882,wh:119505,xh:63595,yh:63349,zh:95101,Ah:75240,Bh:27039,Ch:68823,Dh:21537,Eh:83464,Fh:75707,Gh:83113,Hh:101952,Ih:101953,Kh:79610,Lh:24402,Mh:24400,Nh:32925,Oh:57173,Ph:122502,Qh:64423,Rh:64424,Sh:33986,Th:100828,Uh:21409,Vh:11070,Wh:11074,Xh:17880,Yh:14001,ai:30709,bi:30707,ci:30711,di:30710,
fi:30708,Zh:26984,gi:63648,hi:63649,ii:51879,ji:111059,ki:5754,li:20445,mi:110386,ni:113746,oi:66557,ri:17310,si:28631,ti:21589,vi:68012,wi:60480,xi:31571,yi:76980,zi:41577,Ai:45469,Bi:38669,Ci:13768,Di:13777,Ei:62985,Gi:59369,Hi:43927,Ii:43928,Ji:12924,Ki:100355,Ni:56219,Oi:27669,Pi:10337,Mi:47896,Qi:122629,Ri:121258,Si:107598,Ti:96639,Ui:107536,Vi:96661,Wi:96658,Xi:116646,Yi:121122,Zi:96660,aj:104443,bj:96659,cj:106442,dj:63667,ej:63668,fj:63669,gj:78314,hj:55761,ij:96368,jj:67374,kj:48992,lj:49956,
mj:31961,nj:26388,oj:23811,pj:5E4,rj:47355,sj:47356,tj:37935,uj:45521,vj:21760,wj:83769,xj:49977,yj:49974,zj:93497,Aj:93498,Bj:34325,Cj:115803,Dj:100081,Ej:35309,Fj:68314,Gj:25602,Hj:100339,Ij:59018,Jj:18248,Kj:50625,Lj:9729,Mj:37168,Nj:37169,Oj:21667,Pj:16749,Qj:18635,Rj:39305,Sj:18046,Tj:53969,Uj:8213,Vj:93926,Wj:102852,Xj:110099,Yj:22678,Zj:69076,bk:100856,ck:17736,dk:3832,ek:55759,fk:64031,gk:93044,hk:93045,ik:34388,jk:17657,kk:17655,lk:39579,mk:39578,nk:77448,pk:8196,qk:11357,rk:69877,sk:8197,
tk:82039};function Qj(a,b,c){L.call(this);var d=this;c=c||H("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.C="*";this.l=c;this.sessionId=null;this.channel="widget";this.F=!!a;this.A=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.F&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.C=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.u||0<=Ya(d.u,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.u=this.i=this.m=null;window.addEventListener("message",this.A)}
v(Qj,L);Qj.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.C)}catch(d){lf(d)}}};
Qj.prototype.B=function(){window.removeEventListener("message",this.A);L.prototype.B.call(this)};function Rj(){this.l=[];this.isReady=!1;this.o={};var a=this.i=new Qj(!!H("WIDGET_ID_ENFORCE")),b=this.Va.bind(this);a.m=b;a.u=null;this.i.channel="widget";if(a=H("WIDGET_ID"))this.i.sessionId=a}
m=Rj.prototype;m.Va=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.o[a]||"onReady"===a||(this.addEventListener(a,Sj(this,a)),this.o[a]=!0)):this.oa(a,b,c)};
m.oa=function(){};
function Sj(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.Ga=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.ja());this.sendMessage("onReady");G(this.l,this.Aa,this);this.l=[]};
m.ja=function(){return null};
function Tj(a,b){a.sendMessage("infoDelivery",b)}
m.Aa=function(a){this.isReady?this.i.sendMessage(a):this.l.push(a)};
m.sendMessage=function(a,b){this.Aa({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.i=null};function Uj(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Vj(a,b,c){"string"===typeof a&&(a={mediaContentUrl:a,startSeconds:b,suggestedQuality:c});a:{if((b=a.mediaContentUrl)&&(b=/\/([ve]|embed)\/([^#?]+)/.exec(b))&&b[2]){b=b[2];break a}b=null}a.videoId=b;return Wj(a)}
function Wj(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Xj(a,b,c,d){if(C(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Yj(a){Rj.call(this);this.h=a;this.j=[];this.addEventListener("onReady",E(this.Sa,this));this.addEventListener("onVideoProgress",E(this.bb,this));this.addEventListener("onVolumeChange",E(this.cb,this));this.addEventListener("onApiChange",E(this.Wa,this));this.addEventListener("onPlaybackQualityChange",E(this.Ya,this));this.addEventListener("onPlaybackRateChange",E(this.Za,this));this.addEventListener("onStateChange",E(this.ab,this));this.addEventListener("onWebglSettingsChanged",E(this.eb,
this))}
v(Yj,Rj);m=Yj.prototype;m.oa=function(a,b,c){if(this.h.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Uj(a)){var d=b;if(C(d[0])&&!Array.isArray(d[0]))d=d[0];else{var e={};switch(a){case "loadVideoById":case "cueVideoById":e=Wj.apply(window,d);break;case "loadVideoByUrl":case "cueVideoByUrl":e=Vj.apply(window,d);break;case "loadPlaylist":case "cuePlaylist":e=Xj.apply(window,d)}d=e}b.length=1;b[0]=d}this.h.handleExternalCall(a,b,c);Uj(a)&&Tj(this,this.ja())}};
m.Sa=function(){var a=this.Ga.bind(this);this.i.i=a};
m.addEventListener=function(a,b){this.j.push({eventType:a,listener:b});this.h.addEventListener(a,b)};
m.ja=function(){if(!this.h)return null;var a=this.h.getApiInterface();cb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.h[e]();b[f]=g}catch(h){}}}b.videoData=this.h.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.ab=function(a){a={playerState:a,currentTime:this.h.getCurrentTime(),duration:this.h.getDuration(),videoData:this.h.getVideoData(),videoStartBytes:0,videoBytesTotal:this.h.getVideoBytesTotal(),videoLoadedFraction:this.h.getVideoLoadedFraction(),playbackQuality:this.h.getPlaybackQuality(),availableQualityLevels:this.h.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.h.getPlaybackRate(),mediaReferenceTime:this.h.getMediaReferenceTime()};this.h.getVideoUrl&&(a.videoUrl=
this.h.getVideoUrl());this.h.getVideoContentRect&&(a.videoContentRect=this.h.getVideoContentRect());this.h.getProgressState&&(a.progressState=this.h.getProgressState());this.h.getPlaylist&&(a.playlist=this.h.getPlaylist());this.h.getPlaylistIndex&&(a.playlistIndex=this.h.getPlaylistIndex());this.h.getStoryboardFormat&&(a.storyboardFormat=this.h.getStoryboardFormat());Tj(this,a)};
m.Ya=function(a){Tj(this,{playbackQuality:a})};
m.Za=function(a){Tj(this,{playbackRate:a})};
m.Wa=function(){for(var a=this.h.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.h.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.h.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.cb=function(){Tj(this,{muted:this.h.isMuted(),volume:this.h.getVolume()})};
m.bb=function(a){a={currentTime:a,videoBytesLoaded:this.h.getVideoBytesLoaded(),videoLoadedFraction:this.h.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.h.getPlaybackRate(),mediaReferenceTime:this.h.getMediaReferenceTime()};this.h.getProgressState&&(a.progressState=this.h.getProgressState());Tj(this,a)};
m.eb=function(){var a={sphericalProperties:this.h.getSphericalProperties()};Tj(this,a)};
m.dispose=function(){Rj.prototype.dispose.call(this);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.h.removeEventListener(b.eventType,b.listener)}this.j=[]};function Zj(){var a=mb(ak),b;return De(new M(function(c,d){a.onSuccess=function(e){cg(e)?c(e):d(new bk("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new bk("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new bk("Request timed out","net.timeout",e))};
b=ig("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Ee&&b.abort();
return Be(c)})}
function bk(a,b,c){Va.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(bk,Va);function ck(){this.i=0;this.h=null}
ck.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),we(a)?a:dk(a)):2===this.i&&b?(a=b.call(c,this.h),we(a)?a:ek(a)):this};
ck.prototype.getValue=function(){return this.h};
ck.prototype.$goog_Thenable=!0;function ek(a){var b=new ck;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function dk(a){var b=new ck;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function fk(a){Va.call(this,a.message||a.description||a.name);this.isMissing=a instanceof gk;this.isTimeout=a instanceof bk&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Ee}
v(fk,Va);fk.prototype.name="BiscottiError";function gk(){Va.call(this,"Biscotti ID is missing from server")}
v(gk,Va);gk.prototype.name="BiscottiMissingError";var ak={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},hk=null;
function Of(){if(Q("disable_biscotti_fetch_on_html5_clients"))return Be(Error("Fetching biscotti ID is disabled."));if(Q("condition_biscotti_fetch_on_consent_cookie_html5_clients")&&!Yc.get("CONSENT","").startsWith("YES+"))return Be(Error("User has not consented - not fetching biscotti id."));if("1"==kb())return Be(Error("Biscotti ID is not available in private embed mode"));hk||(hk=De(Zj().then(ik),function(a){return jk(2,a)}));
return hk}
function ik(a){a=a.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new gk;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new gk;a=a.id;Pf(a);hk=dk(a);kk(18E5,2);return a}
function jk(a,b){b=new fk(b);Pf("");hk=ek(b);0<a&&kk(12E4,a-1);throw b;}
function kk(a,b){R(function(){De(Zj().then(ik,function(c){return jk(b,c)}),Ia)},a)}
function lk(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Of()}catch(b){return Be(b)}}
;function mk(a){if("1"!=kb()){a&&Nf();try{lk().then(function(){},function(){}),R(mk,18E5)}catch(b){kf(b)}}}
;var nk=Date.now().toString();
function ok(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(nk)for(a=1,b=0;b<nk.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^nk.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var pk,qk=y.ytLoggingDocDocumentNonce_;qk||(qk=ok(),Sa("ytLoggingDocDocumentNonce_",qk));pk=qk;var rk={Pd:0,Ob:1,Wb:2,Ug:3,Rd:4,ak:5,Jh:6,Li:7,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE"};function sk(a){this.h=a}
function tk(a){return new sk({trackingParams:a})}
sk.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
sk.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
sk.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function uk(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function vk(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function wk(a){return H(vk(void 0===a?0:a),void 0)}
A("yt_logging_screen.getRootVeType",wk,void 0);function xk(a){return(a=wk(void 0===a?0:a))?new sk({veType:a,youtubeData:void 0}):null}
function yk(){var a=H("csn-to-ctt-auth-info");a||(a={},O("csn-to-ctt-auth-info",a));return a}
function zk(a){a=void 0===a?0:a;var b=H(uk(a));if(!b&&!H("USE_CSN_FALLBACK",!0))return null;b||0!=a||(b="UNDEFINED_CSN");return b?b:null}
A("yt_logging_screen.getCurrentCsn",zk,void 0);function Ak(a,b,c){var d=yk();(c=zk(c))&&delete d[c];b&&(d[a]=b)}
function Bk(a){return yk()[a]}
A("yt_logging_screen.getCttAuthInfo",Bk,void 0);function Ck(a,b,c,d){c=void 0===c?0:c;if(a!==H(uk(c))||b!==H(vk(c)))Ak(a,d,c),O(uk(c),a),O(vk(c),b),b=function(){setTimeout(function(){a&&fh("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:pk,clientScreenNonce:a},Yi)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
A("yt_logging_screen.setCurrentScreen",Ck,void 0);function Dk(a){yh.call(this,1,arguments);this.csn=a}
v(Dk,yh);var Hh=new zh("screen-created",Dk),Ek=[],Gk=Fk,Hk=0;function Ik(a,b,c,d){c={csn:b,parentVe:c.getAsJson(),childVes:$a(d,function(f){return f.getAsJson()})};
d=u(d);for(var e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(ib(e)||!e.trackingParams&&!e.veType)&&pj(Error("Child VE logged with no data"));d={D:Bk(b),M:b};"UNDEFINED_CSN"==b?Jk("visualElementAttached",c,d):a?fh("visualElementAttached",c,a,d):Zi("visualElementAttached",c,d)}
function Fk(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return xc(b)}
function Jk(a,b,c){Ek.push({payloadName:a,payload:b,options:c});Hk||(Hk=Ih())}
function Jh(a){if(Ek){for(var b=u(Ek),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,fh(c.payloadName,c.payload,null,c.options));Ek.length=0}Hk=0}
;function Kk(){this.i=new Set;this.h=new Set;this.j=new Map}
Kk.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Ja(Kk);function Lk(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!Mk(a)||c.some(function(e){return!Mk(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())Nk(a,d.value);return a}
function Nk(a,b){for(var c in b)if(Mk(b[c])){if(c in a&&!Mk(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Nk(a[c],b[c])}else if(Ok(b[c])){if(c in a&&!Ok(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Pk(a[c],b[c])}else a[c]=b[c];return a}
function Pk(a,b){b=u(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Mk(c)?a.push(Nk({},c)):Ok(c)?a.push(Pk([],c)):a.push(c);return a}
function Mk(a){return"object"===typeof a&&!Array.isArray(a)}
function Ok(a){return"object"===typeof a&&Array.isArray(a)}
;function Qk(a,b){yh.call(this,1,arguments)}
v(Qk,yh);function Rk(a,b){yh.call(this,1,arguments)}
v(Rk,yh);var Sk=new zh("aft-recorded",Qk),Tk=new zh("timing-sent",Rk);var Uk=window;function Vk(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var Wk=Uk.performance||Uk.mozPerformance||Uk.msPerformance||Uk.webkitPerformance||new Vk;var Xk=!1;E(Wk.clearResourceTimings||Wk.webkitClearResourceTimings||Wk.mozClearResourceTimings||Wk.msClearResourceTimings||Wk.oClearResourceTimings||Ia,Wk);function Yk(a){var b=Zk(a);if(b.aft)return b.aft;a=H((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function $k(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Sa("ytcsi."+(a||"")+"data_",b));return b}
function al(a){a=$k(a);a.info||(a.info={});return a.info}
function Zk(a){a=$k(a);a.tick||(a.tick={});return a.tick}
function bl(a){var b=$k(a).nonce;b||(b=ok(),$k(a).nonce=b);return b}
function cl(a){var b=Zk(a||""),c=Yk(a);c&&!Xk&&(Eh(Sk,new Qk(Math.round(c-b._start),a)),Xk=!0)}
;function dl(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a,void 0),A("ytcsi.reference",{},void 0));return a}
function el(a){a=a||"";var b=B("ytcsi.reference");b||(dl(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=dl(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var fl=y.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",fl,void 0);function gl(){this.h=0}
function hl(){gl.h||(gl.h=new gl);return gl.h}
gl.prototype.tick=function(a,b,c){il(this,"tick_"+a+"_"+b)||Zi("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c})};
gl.prototype.info=function(a,b){var c=Object.keys(a).join("");il(this,"info_"+c+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,Zi("latencyActionInfo",a))};
gl.prototype.span=function(a,b){var c=Object.keys(a).join("");il(this,"span_"+c+"_"+b)||(a.clientActionNonce=b,Zi("latencyActionSpan",a))};
function il(a,b){fl[b]=fl[b]||{count:0};var c=fl[b];c.count++;c.time=S();a.h||(a.h=Ef(function(){var d=S(),e;for(e in fl)fl[e]&&6E4<d-fl[e].time&&delete fl[e];a&&(a.h=0)},0,5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||pj(c)),!0):!1}
;var Y={},jl=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an="adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid=
"requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",
Y.pnt="performanceNavigationTiming",Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",Y.GetSettings_rid=
"requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),kl="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),ml={},nl=(ml.ccs="CANARY_STATE_",ml.mver="MEASUREMENT_VERSION_",
ml.pis="PLAYER_INITIALIZED_STATE_",ml.yt_pt="LATENCY_PLAYER_",ml.pa="LATENCY_ACTION_",ml.yt_vst="VIDEO_STREAM_TYPE_",ml),ol="all_vc ap aq c cver cbrand cmodel cplatform ctheme ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function pl(a){return!!H("FORCE_CSI_ON_GEL",!1)||Q("csi_on_gel")||!!$k(a).useGel}
function ql(a){a=$k(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
;function rl(a,b,c){if(null!==b)if(al(c)[a]=b,pl(c)){var d=b;b=ql(c);if(b.gelInfos)b.gelInfos["info_"+a]=!0;else{var e={};b.gelInfos=(e["info_"+a]=!0,e)}if(a.match("_rid")){var f=a.split("_rid")[0];a="REQUEST_ID"}if(a in jl){b=jl[a];0<=Ya(kl,b)&&(d=!!d);a in nl&&"string"===typeof d&&(d=nl[a]+d.toUpperCase());a=d;d=b.split(".");for(var g=e={},h=0;h<d.length-1;h++){var k=d[h];g[k]={};g=g[k]}g[d[d.length-1]]="requestIds"===b?[{id:a,endpoint:f}]:a;f=Lk({},e)}else 0<=Ya(ol,a)||pj(new U("Unknown label logged with GEL CSI",
a)),f=void 0;f&&pl(c)&&(b=el(c||""),Lk(b.info,f),b=ql(c),b.gelInfos||(b.gelInfos={}),Lk(b.gelInfos,f),c=bl(c),hl().info(f,c))}else el(c||"").info[a]=b}
function sl(a,b,c){var d=Zk(c);if(!b&&"_"!==a[0]){var e=a;Wk.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),Wk.mark(e))}e=b||S();d[a]=e;e=ql(c);e.gelTicks&&(e.gelTicks["tick_"+a]=!0);c||b||S();if(pl(c)){el(c||"").tick[a]=b||S();e=bl(c);if("_start"===a){var f=hl();il(f,"baseline_"+e)||Zi("latencyActionBaselined",{clientActionNonce:e},{timestamp:b})}else hl().tick(a,e,b);cl(c);e=!0}else e=!1;if(!e){if(!B("yt.timing."+(c||"")+"pingSent_")&&(f=H((c||"")+"TIMING_ACTION",void 0),e=
Zk(c),B("ytglobal.timing"+(c||"")+"ready_")&&f&&"_start"in Zk(void 0)&&Yk(c)))if(cl(c),c)tl(c);else{f=!0;var g=H("TIMING_WAIT",[]);if(g.length)for(var h=0,k=g.length;h<k;++h)if(!(g[h]in e)){f=!1;break}f&&tl(c)}el(c||"").tick[a]=b||S()}return d[a]}
function tl(a){if(!pl(a)){var b=Zk(a),c=al(a),d=b._start,e=H("CSI_SERVICE_NAME","youtube"),f={v:2,s:e,action:H((a||"")+"TIMING_ACTION",void 0)},g=c.srt;void 0!==b.srt&&delete c.srt;b.aft=Yk(a);var h=Zk(a),k=h.pbr,l=h.vc;h=h.pbs;k&&l&&h&&k<l&&l<h&&al(a).yt_pvis&&"youtube"===e&&(rl("yt_lt","hot_bg",a),e=b.vc,k=b.pbs,delete b.aft,c.aft=Math.round(k-e));for(var p in c)"_"!==p.charAt(0)&&(f[p]=c[p]);b.ps=S();p={};e=[];for(var n in b)"_"!==n.charAt(0)&&(k=Math.round(b[n]-d),p[n]=k,e.push(n+"."+k));f.rt=
e.join(",");b=!!c.ap;c="";for(var q in f)f.hasOwnProperty(q)&&(c+="&"+q+"="+f[q]);f="/csi_204?"+c.substring(1);window.navigator&&window.navigator.sendBeacon&&(b||Q("always_send_csi_204_with_beacon"))?xg(f):ug(f);A("yt.timing."+(a||"")+"pingSent_",!0,void 0);Eh(Tk,new Rk(p.aft+(Number(g)||0),a))}}
var ul=window;ul.ytcsi&&(ul.ytcsi.info=rl,ul.ytcsi.tick=sl);function vl(){this.l=[];this.o=[];this.h=[];this.i=new Set;this.m=new Map}
function wl(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=zk(c),h=xk(c);g&&h&&(d.csn=g,(null===(e=d.response)||void 0===e?0:e.trackingParams)&&Ik(a.client,g,h,[tk(d.response.trackingParams)]),(null===(f=d.playerResponse)||void 0===f?0:f.trackingParams)&&Ik(a.client,g,h,[tk(d.playerResponse.trackingParams)]))})}
function xl(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.l.push([b,c]);else{var e=zk(d);c=c||xk(d);e&&c&&Ik(a.client,e,c,[b])}}
vl.prototype.clickCommand=function(a,b,c){c=zk(void 0===c?0:c);if(!a.clickTrackingParams||!c)return!1;var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:tk(a.clickTrackingParams).getAsJson(),gestureType:e};b&&(a.clientData=b);b={D:Bk(c),M:c};"UNDEFINED_CSN"==c?Jk("visualElementGestured",a,b):d?fh("visualElementGestured",a,d,b):Zi("visualElementGestured",a,b);return!0};
function yl(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){zl(a,b,c);var f=xk(c.layer);if(f){for(var g=u(a.l),h=g.next();!h.done;h=g.next())h=h.value,xl(a,h[0],h[1]||f,c.layer);f=u(a.o);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=zk(g);var l=k[0]||xk(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={D:Bk(h),M:h},"UNDEFINED_CSN"==h?Jk("visualElementStateChanged",k,l):g?fh("visualElementStateChanged",k,g,l):Zi("visualElementStateChanged",
k,l))}}};
zk(c.layer)||a.j();if(c.ta)for(var d=u(c.ta),e=d.next();!e.done;e=d.next())wl(a,e.value,c.layer);else qj(Error("Delayed screen needs a data promise."))}
function zl(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Ta?c.Ta:c.layer;var e=zk(d);d=xk(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));try{var g=a.client,h=f,k=c.sa,l=c.D,p=Gk(),n={csn:p,pageVe:(new sk({veType:b,youtubeData:void 0})).getAsJson()};h&&h.visualElement?n.implicitGesture={parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()}:h&&pj(new U("newScreen() parent element does not have a VE - rootVe",
b));k&&(n.cloneCsn=k);k={D:l,M:p};g?fh("screenCreated",n,g,k):Zi("screenCreated",n,k);Eh(Hh,new Dk(p));var q=p}catch(r){rj(r,{Dk:b,rootVe:d,parentVisualElement:void 0,yk:e,Ck:f,sa:c.sa});qj(r);return}Ck(q,b,c.layer,c.D);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=Q("screen_manager_skip_hide_killswitch"))){a:{b=u(Object.values(rk));for(f=b.next();!f.done;f=b.next())if(zk(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,g=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:g},f={D:Bk(e),M:e,
Fa:f},"UNDEFINED_CSN"==e?Jk("visualElementHidden",d,f):b?fh("visualElementHidden",d,b,f):Zi("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=q||"");rl("csn",q);Kk.getInstance().clear();d=xk(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(Q("web_mark_root_visible")||Q("music_web_mark_root_visible"))&&(e=q,q=Q("use_default_events_client")?void 0:Yi,b={csn:e,ve:d.getAsJson(),eventType:1},f={D:Bk(e),M:e},"UNDEFINED_CSN"==e?Jk("visualElementShown",b,f):q?fh("visualElementShown",
b,q,f):Zi("visualElementShown",b,f));a.i.delete(c.layer||0);a.j=void 0;e=u(a.m);for(q=e.next();!q.done;q=e.next())q=u(q.value),b=q.next().value,q.next().value.has(c.layer)&&d&&xl(a,b,d,c.layer)}
;function Al(a){L.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.za,this)}
v(Al,L);m=Al.prototype;m.start=function(){this.started||this.h||(this.started=!0,this.connection.P("RECEIVING"))};
m.P=function(a,b){this.started&&!this.h&&this.connection.P(a,b)};
m.za=function(a,b,c){if(this.started&&!this.h){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Bl(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Cl(a,c))&&this.P(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Xa.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Xa=function(a,b){this.started&&!this.h&&this.connection.P(a,this.ia(a,b))};
m.ia=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.B=function(){var a=this.connection;a.h||Oe(a.i,"command",this.za,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);L.prototype.B.call(this)};function Dl(a,b){Al.call(this,b);this.api=a;this.start()}
v(Dl,Al);Dl.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Dl.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Bl(a,b){switch(a){case "loadVideoById":return a=Wj(b),[a];case "cueVideoById":return a=Wj(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Xj(b),[a];case "cuePlaylist":return a=Xj(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Cl(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Dl.prototype.ia=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Al.prototype.ia.call(this,a,b)};
Dl.prototype.B=function(){Al.prototype.B.call(this);delete this.api};function El(a){a=void 0===a?!1:a;L.call(this);this.i=new N(a);Ad(this,Ra(yd,this.i))}
F(El,L);El.prototype.subscribe=function(a,b,c){return this.h?0:this.i.subscribe(a,b,c)};
El.prototype.l=function(a,b){this.h||this.i.O.apply(this.i,arguments)};function Fl(a,b,c){El.call(this);this.j=a;this.destination=b;this.id=c}
v(Fl,El);Fl.prototype.P=function(a,b){this.h||this.j.P(this.destination,this.id,a,b)};
Fl.prototype.B=function(){this.destination=this.j=null;El.prototype.B.call(this)};function Gl(a,b,c){L.call(this);this.destination=a;this.origin=c;this.i=xf(window,"message",this.j.bind(this));this.connection=new Fl(this,a,b);Ad(this,Ra(yd,this.connection))}
v(Gl,L);Gl.prototype.P=function(a,b,c,d){this.h||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(qe(a),this.origin))};
Gl.prototype.j=function(a){var b;if(b=!this.h)if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h||c.l("command",b.command,b.data,a.origin))}};
Gl.prototype.B=function(){yf(this.i);this.destination=null;L.prototype.B.call(this)};function Hl(){L.call(this);this.i=[]}
v(Hl,L);Hl.prototype.B=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.Da)}L.prototype.B.call(this)};function Il(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||mb(b);this.assets=a.assets||{};this.attrs=a.attrs||mb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Il.prototype.clone=function(){var a=new Il,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ka(c)?a[b]=mb(c):a[b]=c}return a};var Jl=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Kl(a){a=a||"";if(window.spf){var b=a.match(Jl);spf.style.load(a,b?b[1]:"",void 0)}else Ll(a)}
function Ll(a){var b=Ml(a),c=document.getElementById(b),d=c&&uj(c,"loaded");d||c&&!d||(c=Nl(a,b,function(){uj(c,"loaded")||(sj(c),Fg(b),R(Ra(Gg,b),0))}))}
function Nl(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Nc(a);d.rel="stylesheet";d.href=ub(a).toString();(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Ml(a){var b=Fc(document,"A");Rb(b,new I(a,Eb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Ub(a)}
;function Ol(a,b,c,d){L.call(this);var e=this;this.F=b;this.webPlayerContextConfig=d;this.fa=!1;this.api={};this.T=this.m=null;this.I=new N;this.i={};this.K=this.Z=this.elementId=this.ga=this.config=null;this.J=!1;this.l=this.A=null;this.aa={};this.Ba=["onReady"];this.lastError=null;this.qa=NaN;this.C={};this.Ca=new Hl(this);this.S=0;this.j=this.u=a;Ad(this,Ra(yd,this.I));Pl(this);Ql(this);Ad(this,Ra(yd,this.Ca));c?this.S=R(function(){e.loadNewVideoConfig(c)},0):d&&(Rl(this),Sl(this))}
v(Ol,L);m=Ol.prototype;m.getId=function(){return this.F};
m.loadNewVideoConfig=function(a){if(!this.h){this.S&&(Af(this.S),this.S=0);var b=a||{};b instanceof Il||(b=new Il(b));this.config=b;this.setConfig(a);Sl(this);this.isReady()&&Tl(this)}};
function Rl(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.F,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.F:a.config.attrs.id=a.F);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.ga=a;this.config=Ul(a);Rl(this);this.Z||(this.Z=Vl(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Pc(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Pc(Number(a)||a))};
function Tl(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function Wl(a){var b=!0,c=Xl(a);c&&a.config&&(a=Yl(a),b=uj(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function Sl(a){if(!a.h&&!a.J){var b=Wl(a);if(b&&"html5"===(Xl(a)?"html5":null))a.K="html5",a.isReady()||Zl(a);else if($l(a),a.K="html5",b&&a.l&&a.u)a.u.appendChild(a.l),Zl(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.A=function(){c=!0;var d=am(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?Ul(a.config):void 0;d&&d(a.u,e,a.webPlayerContextConfig);Zl(a)};
a.J=!0;b?a.A():(yj(Yl(a),a.A),(b=bm(a))&&Kl(b),cm(a)&&!c&&A("yt.player.Application.create",null,void 0))}}}
function Xl(a){var b=Bc(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Zl(a){var b;if(!a.h){var c=Xl(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.J=!1,!am(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||dm(a)):a.qa=R(function(){Zl(a)},50)}}
function dm(a){Pl(a);a.fa=!0;var b=Xl(a);if(b){a.m=em(a,b,"addEventListener");a.T=em(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=em(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.m&&a.m(g,a.i[g]);Tl(a);a.Z&&a.Z(a.api);a.I.O("onReady",a.api)}
function em(a,b,c){var d=b[c];return function(e){for(var f=[],g=0;g<arguments.length;++g)f[g-0]=arguments[g];try{return a.lastError=null,d.apply(b,f)}catch(h){"sendAbandonmentPing"!==c&&(h.params=c,a.lastError=h,lf(h))}}}
function Pl(a){a.fa=!1;if(a.T)for(var b in a.i)a.i.hasOwnProperty(b)&&a.T(b,a.i[b]);for(var c in a.C)a.C.hasOwnProperty(c)&&Af(Number(c));a.C={};a.m=null;a.T=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.ga};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.fa};
function Ql(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Fg("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Fg("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){Fg("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=Vl(this,b);d&&(0<=Ya(this.Ba,a)||this.i[a]||(b=fm(this,a),this.m&&this.m(a,b)),this.I.subscribe(a,d),"onReady"===a&&this.isReady()&&R(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h||(b=Vl(this,b))&&Oe(this.I,a,b)};
function Vl(a,b){var c=b;if("string"===typeof b){if(a.aa[b])return a.aa[b];c=function(d){for(var e=[],f=0;f<arguments.length;++f)e[f-0]=arguments[f];(f=B(b))&&f.apply(y,e)};
a.aa[b]=c}return c?c:null}
function fm(a,b){var c="ytPlayer"+b+a.F;a.i[b]=c;y[c]=function(d){var e=R(function(){if(!a.h){a.I.O(b,d);var f=a.C,g=String(e);g in f&&delete f[g]}},0);
jb(a.C,String(e))};
return c}
m.getPlayerType=function(){return this.K||(Xl(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function $l(a){a.cancel();Pl(a);a.K=null;a.config&&(a.config.loaded=!1);var b=Xl(a);b&&(Wl(a)||!cm(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.u)for(a=a.u;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.A&&Ej(Yl(this),this.A);Af(this.qa);this.J=!1};
m.B=function(){$l(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){kf(b)}this.aa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.ga=this.config=this.api=null;delete this.u;delete this.j;L.prototype.B.call(this)};
function cm(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Yl(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function bm(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function am(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===Sf(d||"","&")[b]}
function Ul(a){for(var b={},c=u(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?mb(e):e}return b}
;var gm={},hm="player_uid_"+(1E9*Math.random()>>>0);function im(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?Bc(d):d;var e=hm+"_"+Ma(d),f=gm[e];if(f&&c)return jm(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Ol(d,e,a,b);gm[e]=f;Fg("player-added",f.api);Ad(f,function(){delete gm[f.getId()]});
return f.api}
function jm(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var km=null,lm=null,mm=null;function nm(){var a=km.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function om(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=H("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=H("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=Xb(window.location.href);g&&f.push(g);g=Xb(d);if(0<=Ya(f,g)||!g&&0==d.lastIndexOf("/",0))if(Q("autoescape_tempdata_url")&&(f=document.createElement("a"),Rb(f,d),d=f.href),d){g=d.match(Vb);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:zk()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&(e=b,b="ST-"+Ub(d).toString(36),e=e?Zb(e):"",hh(b,e,k||5))}else k=b,e="ST-"+Ub(d).toString(36),k=k?Zb(k):"",hh(e,k,5)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var p=void 0===p?"":p;var n=void 0===n?window:n;c=n.location;a=$b(a,l)+p;a=a instanceof I?a:Jb(a);c.href=Fb(a)}return!0}
;A("yt.setConfig",O,void 0);A("yt.config.set",O,void 0);A("yt.setMsg",nf,void 0);A("yt.msgs.set",nf,void 0);A("yt.logging.errors.log",qj,void 0);
A("writeEmbed",function(){var a=H("PLAYER_CONFIG",void 0);if(!a){var b=H("PLAYER_VARS",void 0);b&&(a={args:b})}mk(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=H("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);if((c=H("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){c=c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;
if(!c.serializedForcedExperimentIds){var d=window.location.href;-1!=d.indexOf("?")?(d=(d||"").split("#")[0],d=d.split("?",2),d=Wf(1<d.length?d[1]:d[0])):d={};d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}km=im(a,c,!1)}else km=im(a);km.addEventListener("onVideoDataChange",nm);a=H("POST_MESSAGE_ID","player");H("ENABLE_JS_API")?mm=new Yj(km):H("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(lm=new Gl(window.parent,a,b),mm=new Dl(km,lm.connection));Hj()},
void 0);
var pm=jf(function(){sl("ol");var a=ih.getInstance(),b=!!((lh("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&Dd(document.body,"exp-invert-logo"))if(c&&!Dd(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Dd(d,"inverted-hdpi")){var e=Bd(d);Cd(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Dd(document.body,"inverted-hdpi")&&Ed();if(b!=c){b="f"+(Math.floor(119/31)+1);d=lh(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete T[b]:(c=d.toString(16),T[b]=c.toString());c=!0;Q("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in T)d.push(f+"="+encodeURIComponent(String(T[f])));hh(b,d.join("&"),63072E3,a.i,c)}vl.h||(vl.h=new vl);a=vl.h;f=16623;var g=void 0===g?{}:g;Object.values(Pj).includes(f)||(pj(new U("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.l=[];a.o=[];g.ta?yl(a,f,g):zl(a,f,g)}),qm=jf(function(){km&&
km.sendAbandonmentPing&&km.sendAbandonmentPing();
H("PL_ATT")&&Mj.dispose();for(var a=0,b=Fj.length;a<b;a++)Hf(Fj[a]);Fj.length=0;Dj("//static.doubleclick.net/instream/ad_status.js");Gj=!1;O("DCLKSTAT",0);zd(mm,lm);km&&(km.removeEventListener("onVideoDataChange",nm),km.destroy())});
window.addEventListener?(window.addEventListener("load",pm),window.addEventListener("unload",qm)):window.attachEvent&&(window.attachEvent("onload",pm),window.attachEvent("onunload",qm));Sa("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Nj);Sa("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||Oj);Sa("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||Ij);
Sa("yt.player.exports.navigate",B("yt.player.exports.navigate")||om);Sa("yt.util.activity.init",B("yt.util.activity.init")||Jf);Sa("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||Mf);Sa("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||Kf);}).call(this);
