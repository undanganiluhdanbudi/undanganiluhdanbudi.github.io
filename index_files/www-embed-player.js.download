(function(){'use strict';var r;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function u(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
var ha=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},ja=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ka;
if(typeof Object.setPrototypeOf=="function")ka=Object.setPrototypeOf;else{var la;a:{var ma={a:!0},oa={};try{oa.__proto__=ma;la=oa.a;break a}catch(a){}la=!1}ka=la?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var pa=ka;
function w(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(pa)pa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function z(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function qa(a){if(!(a instanceof Array)){a=z(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ra(a){return sa(a,a)}
function sa(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function ta(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ua=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ta(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ua});
function va(){this.B=!1;this.u=null;this.i=void 0;this.h=1;this.D=this.o=0;this.R=this.j=null}
function wa(a){if(a.B)throw new TypeError("Generator is already running");a.B=!0}
va.prototype.H=function(a){this.i=a};
function xa(a,b){a.j={exception:b,hd:!0};a.h=a.o||a.D}
va.prototype.return=function(a){this.j={return:a};this.h=this.D};
va.prototype.yield=function(a,b){this.h=b;return{value:a}};
va.prototype.F=function(a){this.h=a};
function ya(a,b,c){a.o=b;c!=void 0&&(a.D=c)}
function za(a){a.o=0;var b=a.j.exception;a.j=null;return b}
function Aa(a){var b=a.R.splice(0)[0];(b=a.j=a.j||b)?b.hd?a.h=a.o||a.D:b.F!=void 0&&a.D<b.F?(a.h=b.F,a.j=null):a.h=a.D:a.h=0}
function Ba(a){this.h=new va;this.i=a}
function Ca(a,b){wa(a.h);var c=a.h.u;if(c)return Da(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ea(a)}
function Da(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.B=!1,e;var f=e.value}catch(g){return a.h.u=null,xa(a.h,g),Ea(a)}a.h.u=null;d.call(a.h,f);return Ea(a)}
function Ea(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.B=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.B=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.hd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Fa(a){this.next=function(b){wa(a.h);a.h.u?b=Da(a,a.h.u.next,b,a.h.H):(a.h.H(b),b=Ea(a));return b};
this.throw=function(b){wa(a.h);a.h.u?b=Da(a,a.h.u["throw"],b,a.h.H):(xa(a.h,b),b=Ea(a));return b};
this.return=function(b){return Ca(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ga(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ga(new Fa(new Ba(a)))}
function B(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return ja});
u("Reflect.setPrototypeOf",function(a){return a?a:pa?function(b,c){try{return pa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.B=!1;var h=this.o();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.D()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.D=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.o=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.Z),reject:g(this.D)}};
b.prototype.Z=function(g){if(g===this)this.D(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ja(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.Y(g):this.u(g)}};
b.prototype.Y=function(g){var h=void 0;try{h=g.then}catch(k){this.D(k);return}typeof h=="function"?this.ta(h,g):this.u(g)};
b.prototype.D=function(g){this.H(2,g)};
b.prototype.u=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(this.h!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;this.h===2&&this.ga();this.R()};
b.prototype.ga=function(){var g=this;e(function(){if(g.U()){var h=ea.console;typeof h!=="undefined"&&h.error(g.j)}},1)};
b.prototype.U=function(){if(this.B)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.R=function(){if(this.i!=null){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ja=function(g){var h=this.o();g.Yb(h.resolve,h.reject)};
b.prototype.ta=function(g,h){var k=this.o();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(p,t){return typeof p=="function"?function(v){try{l(p(v))}catch(x){m(x)}}:t}
var l,m,n=new b(function(p,t){l=p;m=t});
this.Yb(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Yb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;this.i==null?f.i(k):this.i.push(k);this.B=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=z(g),m=l.next();!m.done;m=l.next())d(m.value).Yb(h,k)})};
b.all=function(g){var h=z(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(v){return function(x){p[v]=x;t--;t==0&&l(p)}}
var p=[],t=0;do p.push(void 0),t++,d(k.value).Yb(n(p.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||pa});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("globalThis",function(a){return a||ea});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=z(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ta(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ta(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ta(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return fa(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ta(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=z(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(z([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=z(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(z([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Ha(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ha(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ha(this,function(b){return b})}});
function Ia(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ia(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Ha(this,function(b,c){return c})}});
u("Math.clz32",function(a){return a?a:function(b){b=Number(b)>>>0;if(b===0)return 32;var c=0;(b&4294901760)===0&&(b<<=16,c+=16);(b&4278190080)===0&&(b<<=8,c+=8);(b&4026531840)===0&&(b<<=4,c+=4);(b&3221225472)===0&&(b<<=2,c+=2);(b&2147483648)===0&&c++;return c}});
u("Math.log10",function(a){return a?a:function(b){return Math.log(b)/Math.LN10}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ka=Ka||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||typeof c.execScript=="undefined"||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function La(a,b){var c=E("CLOSURE_FLAGS");a=c&&c[a];return a!=null?a:b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function Oa(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Pa(a){var b=Oa(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Qa(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(Math.random()*1E9>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Wa(a,b,c){Wa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Ua:Va;return Wa.apply(null,arguments)}
function Xa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ya(){return Date.now()}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function $a(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,$a);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
Za($a,Error);$a.prototype.name="CustomError";function ab(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.o=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;var bb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var db=globalThis.trustedTypes,eb;function fb(){var a=null;if(!db)return a;try{var b=function(c){return c};
a=db.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function gb(){eb===void 0&&(eb=fb());return eb}
;function hb(a){this.h=a}
hb.prototype.toString=function(){return this.h+""};
function ib(a){var b=gb();return new hb(b?b.createScriptURL(a):a)}
function jb(a){if(a instanceof hb)return a.h;throw Error("");}
;var kb=ra([""]),lb=sa(["\x00"],["\\0"]),mb=sa(["\n"],["\\n"]),nb=sa(["\x00"],["\\u0000"]);function ob(a){return a.toString().indexOf("`")===-1}
ob(function(a){return a(kb)})||ob(function(a){return a(lb)})||ob(function(a){return a(mb)})||ob(function(a){return a(nb)});function pb(a){this.h=a}
pb.prototype.toString=function(){return this.h};
var qb=new pb("about:invalid#zClosurez");function rb(a){this.ue=a}
function sb(a){return new rb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var tb=[sb("data"),sb("http"),sb("https"),sb("mailto"),sb("ftp"),new rb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],ub=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function vb(a){if(a instanceof pb)if(a instanceof pb)a=a.h;else throw Error("");else a=ub.test(a)?a:void 0;return a}
;function wb(a,b){b=vb(b);b!==void 0&&(a.href=b)}
;function xb(){this.h=yb[0].toLowerCase()}
xb.prototype.toString=function(){return this.h};function zb(a){this.h=a}
zb.prototype.toString=function(){return this.h+""};function Ab(a){var b="true".toString(),c=[new xb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof xb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Bb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;var Cb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Db(a,b){if(b instanceof hb)a.href=jb(b).toString(),a.rel="stylesheet";else{if(Cb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=vb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;function Eb(a){a=a===void 0?document:a;var b,c;a=(c=(b="document"in a?a.document:a).querySelector)==null?void 0:c.call(b,"script[nonce]");return a==null?"":a.nonce||a.getAttribute("nonce")||""}
;function Fb(a){this.h=a}
Fb.prototype.toString=function(){return this.h+""};function Gb(a){var b=Eb(a.ownerDocument&&a.ownerDocument.defaultView||window);b&&a.setAttribute("nonce",b)}
function Hb(a,b){if(b instanceof Fb)b=b.h;else throw Error("");a.textContent=b;Gb(a)}
function Ib(a,b){a.src=jb(b);Gb(a)}
;var Jb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Kb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Lb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Mb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Nb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Kb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Ob(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Pb(a,b){b=Jb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Qb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Pa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Rb(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Sb(a){var b=E("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Tb(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Ub[c])c=Ub[c];else{c=String(c);if(!Ub[c]){var f=/function\s+([^\(]+)/m.exec(c);Ub[c]=f?f[1]:"[Anonymous]"}c=Ub[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Tb(a,b){b||(b={});b[Vb(a)]=!0;var c=a.stack||"",d=a.cause;d&&!b[Vb(d)]&&(c+="\nCaused by: ",d.stack&&d.stack.indexOf(d.toString())==0||(c+=typeof d==="string"?d:d.message+"\n"),c+=Tb(d,b));a=a.errors;if(Array.isArray(a)){d=1;var e;for(e=0;e<a.length&&!(d>4);e++)b[Vb(a[e])]||(c+="\nInner error "+d++ +": ",a[e].stack&&a[e].stack.indexOf(a[e].toString())==0||(c+=typeof a[e]==="string"?a[e]:a[e].message+"\n"),c+=Tb(a[e],b));e<a.length&&(c+="\n... "+(a.length-e)+" more inner errors")}return c}
function Vb(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var Ub={};function Wb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Xb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Yb(a){return a?decodeURI(a):a}
function Zb(a,b){return b.match(Xb)[a]||null}
function $b(a){return Yb(Zb(3,a))}
function ac(a){var b=a.match(Xb);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function bc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function cc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)cc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function dc(a){var b=[],c;for(c in a)cc(c,a[c],b);return b.join("&")}
function ec(a,b){b=dc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function fc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var hc=/#|$/,ic=/[?&]($|#)/;function jc(a,b){for(var c=a.search(hc),d=0,e,f=[];(e=fc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(ic,"$1")}
;function kc(a){var b=b===void 0?Number("34"):b;for(var c=[],d=0;d<lc(a,mc,1).length;d++){var e=lc(a,mc,1)[d];nc(e,2)<=b&&c.push(Number(nc(e,1)))}return c}
function oc(a){var b=b===void 0?Number("34"):b;for(var c=[],d=0;d<lc(a,mc,1).length;d++){var e=lc(a,mc,1)[d];nc(e,2)>b&&c.push(Number(nc(e,1)))}return c}
;function pc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function qc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Pa(d)?qc.apply(null,d):pc(d)}}
;function F(){this.da=this.da;this.D=this.D}
F.prototype.da=!1;F.prototype.dispose=function(){this.da||(this.da=!0,this.aa())};
F.prototype[Symbol.dispose]=function(){this.dispose()};
function rc(a,b){a.addOnDisposeCallback(Xa(pc,b))}
F.prototype.addOnDisposeCallback=function(a,b){this.da?b!==void 0?a.call(b):a():(this.D||(this.D=[]),b&&(a=a.bind(b)),this.D.push(a))};
F.prototype.aa=function(){if(this.D)for(;this.D.length;)this.D.shift()()};var sc;function tc(){F.apply(this,arguments);this.o=1;this[sc]=this.dispose}
w(tc,F);tc.prototype.share=function(){if(this.da)throw Error("E:AD");this.o++;return this};
tc.prototype.dispose=function(){--this.o||F.prototype.dispose.call(this)};
sc=Symbol.dispose;function uc(a){return{fieldType:2,fieldName:a}}
function H(a){return{fieldType:3,fieldName:a}}
;function vc(a){this.h=a;a.Ha("/client_streamz/bg/fic",H("ke"))}
function wc(a){this.h=a;a.Ha("/client_streamz/bg/fiec",H("ke"),uc("ec"))}
function xc(a){this.h=a;a.lb("/client_streamz/bg/fil",H("ke"))}
xc.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fil",a,b)};
function yc(a){this.h=a;a.Ha("/client_streamz/bg/fcc",uc("ph"),H("ke"))}
function zc(a){this.h=a;a.lb("/client_streamz/bg/fcd",uc("ph"),H("ke"))}
zc.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fcd",a,b,c)};
function Ac(a){this.h=a;a.Ha("/client_streamz/bg/fsc",H("ke"))}
function Bc(a){this.h=a;a.lb("/client_streamz/bg/fsl",H("ke"))}
Bc.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fsl",a,b)};
function Cc(a){this.h=a;a.lb("/client_streamz/bg/frs",H("ke"))}
Cc.prototype.record=function(a,b){this.h.record("/client_streamz/bg/frs",a,b)};
function Dc(a){this.h=a;a.lb("/client_streamz/bg/wrl",H("mn"),uc("ac"),uc("sc"),H("rk"),H("mk"))}
Dc.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Ec(a){this.h=a;a.Ha("/client_streamz/bg/ec",H("en"),H("mk"))}
function Fc(a){this.h=a;a.lb("/client_streamz/bg/el",H("en"),H("rk"),H("mk"))}
Fc.prototype.record=function(a,b,c,d){this.h.record("/client_streamz/bg/el",a,b,c,d)};
function Gc(a){this.h=a;a.Ha("/client_streamz/bg/cec",uc("ec"),H("rk"),H("mk"))}
function Hc(a){a.Ha("/client_streamz/bg/po/csc",uc("cs"),H("rk"),H("mk"))}
function Ic(a){a.Ha("/client_streamz/bg/po/ctav",H("av"),H("rk"),H("mk"))}
function Jc(a){a.Ha("/client_streamz/bg/po/cwsc",H("su"),H("rk"),H("mk"))}
;function Kc(a){C.setTimeout(function(){throw a;},0)}
;var Lc=La(610401301,!1),Mc=La(653718497,La(1,!0));function Nc(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Oc,Pc=C.navigator;Oc=Pc?Pc.userAgentData||null:null;function Qc(a){return Lc?Oc?Oc.brands.some(function(b){return(b=b.brand)&&b.indexOf(a)!=-1}):!1:!1}
function J(a){return Nc().indexOf(a)!=-1}
;function Rc(){return Lc?!!Oc&&Oc.brands.length>0:!1}
function Sc(){return Rc()?!1:J("Opera")}
function Tc(){return J("Firefox")||J("FxiOS")}
function Uc(){return Rc()?Qc("Chromium"):(J("Chrome")||J("CriOS"))&&!(Rc()?0:J("Edge"))||J("Silk")}
;function Vc(){return Lc?!!Oc&&!!Oc.platform:!1}
function Wc(){return J("iPhone")&&!J("iPod")&&!J("iPad")}
;var Xc=Sc(),Yc=Rc()?!1:J("Trident")||J("MSIE"),Zc=J("Edge"),$c=J("Gecko")&&!(Nc().toLowerCase().indexOf("webkit")!=-1&&!J("Edge"))&&!(J("Trident")||J("MSIE"))&&!J("Edge"),ad=Nc().toLowerCase().indexOf("webkit")!=-1&&!J("Edge");ad&&J("Mobile");Vc()||J("Macintosh");Vc()||J("Windows");(Vc()?Oc.platform==="Linux":J("Linux"))||Vc()||J("CrOS");var bd=Vc()?Oc.platform==="Android":J("Android");Wc();J("iPad");J("iPod");Wc()||J("iPad")||J("iPod");Nc().toLowerCase().indexOf("kaios");Tc();var cd=Wc()||J("iPod"),dd=J("iPad");!J("Android")||Uc()||Tc()||Sc()||J("Silk");Uc();var ed=J("Safari")&&!(Uc()||(Rc()?0:J("Coast"))||Sc()||(Rc()?0:J("Edge"))||(Rc()?Qc("Microsoft Edge"):J("Edg/"))||(Rc()?Qc("Opera"):J("OPR"))||Tc()||J("Silk")||J("Android"))&&!(Wc()||J("iPad")||J("iPod"));var fd={},gd=null;function hd(a,b){Pa(a);b===void 0&&(b=0);id();b=fd[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function jd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;kd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function kd(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=gd[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
id();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function id(){if(!gd){gd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));fd[c]=d;for(var e=0;e<d.length;e++){var f=d[e];gd[f]===void 0&&(gd[f]=e)}}}}
;var ld=typeof Uint8Array!=="undefined",md=!Yc&&typeof btoa==="function";function nd(a){if(!md)return hd(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var od=/[-_.]/g,pd={"-":"+",_:"/",".":"="};function qd(a){return pd[a]||""}
function rd(a){return ld&&a!=null&&a instanceof Uint8Array}
var sd={};function td(a,b){ud(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
td.prototype.sizeBytes=function(){ud(sd);var a=this.h;if(a!=null&&!rd(a))if(typeof a==="string")if(md){od.test(a)&&(a=a.replace(od,qd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=jd(a);else Oa(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};
var vd;function ud(a){if(a!==sd)throw Error("illegal external caller");}
;var wd;function xd(){var a=Error();Rb(a,"incident");Kc(a)}
function yd(a){a=Error(a);Rb(a,"warning");return a}
;function zd(){return typeof BigInt==="function"}
;function Ad(a){return Array.prototype.slice.call(a)}
;var Bd=typeof Symbol==="function"&&typeof Symbol()==="symbol";function Cd(a){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?Symbol():a}
var Dd=Cd(),Ed=Cd("2ex"),Fd=Cd("1oa");Math.max.apply(Math,qa(Object.values({Zg:1,Xg:2,Wg:4,dh:8,bh:16,ah:32,Ef:64,fh:128,Vg:256,Ug:512,Yg:1024,Kf:2048,eh:4096,Lf:8192,Ff:16384})));var Gd=Bd?function(a,b){a[Dd]|=b}:function(a,b){a.Qa!==void 0?a.Qa|=b:Object.defineProperties(a,{Qa:{value:b,
configurable:!0,writable:!0,enumerable:!1}})},Hd=Bd?function(a){return a[Dd]|0}:function(a){return a.Qa|0},Id=Bd?function(a){return a[Dd]}:function(a){return a.Qa},Jd=Bd?function(a,b){a[Dd]=b}:function(a,b){a.Qa!==void 0?a.Qa=b:Object.defineProperties(a,{Qa:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function Kd(a,b){Jd(b,(a|0)&-30975)}
function Ld(a,b){Jd(b,(a|34)&-30941)}
;var Md={},Nd={};function Od(a){return!(!a||typeof a!=="object"||a.h!==Nd)}
function Pd(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
function Qd(a){return!Array.isArray(a)||a.length?!1:Hd(a)&1?!0:!1}
var Rd,Sd=[];Jd(Sd,55);Rd=Object.freeze(Sd);function Td(a){if(a&2)throw Error();}
var Ud=Object.freeze({});function Vd(a){a.sh=!0;return a}
;var Wd=Vd(function(a){return typeof a==="number"}),Xd=Vd(function(a){return typeof a==="string"}),Yd=Vd(function(a){return typeof a==="boolean"});
function Zd(){var a=$d;return Vd(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
var ae=Vd(function(a){return a!=null&&typeof a==="object"&&typeof a.then==="function"});var be=typeof C.BigInt==="function"&&typeof C.BigInt(0)==="bigint";function ce(a){var b=a;if(Xd(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(Wd(b)&&!Number.isSafeInteger(b))throw Error(String(b));return be?BigInt(a):a=Yd(a)?a?"1":"0":Xd(a)?a.trim()||"0":String(a)}
var ie=Vd(function(a){return be?a>=de&&a<=ee:a[0]==="-"?fe(a,ge):fe(a,he)}),ge=Number.MIN_SAFE_INTEGER.toString(),de=be?BigInt(Number.MIN_SAFE_INTEGER):void 0,he=Number.MAX_SAFE_INTEGER.toString(),ee=be?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function fe(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var je=0,ke=0;function le(a){var b=a>>>0;je=b;ke=(a-b)/4294967296>>>0}
function me(a){if(a<0){le(0-a);var b=z(ne(je,ke));a=b.next().value;b=b.next().value;je=a>>>0;ke=b>>>0}else le(a)}
function oe(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else zd()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+pe(c)+pe(a));return c}
function pe(a){a=String(a);return"0000000".slice(a.length)+a}
function qe(){var a=je,b=ke;b&2147483648?zd()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=z(ne(a,b)),a=b.next().value,b=b.next().value,a="-"+oe(a,b)):a=oe(a,b);return a}
function ne(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function re(a){return a.displayName||a.name||"unknown type name"}
function se(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+Oa(a)+": "+a);return a}
var te=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function ue(a){var b=typeof a;switch(b){case "bigint":return!0;case "number":return Number.isFinite(a)}return b!=="string"?!1:te.test(a)}
function ve(a){if(typeof a!=="number")throw yd("int32");if(!Number.isFinite(a))throw yd("int32");return a|0}
function we(a){return a==null?a:ve(a)}
function xe(a){if(a==null)return a;if(typeof a==="string"){if(!a)return;a=+a}if(typeof a==="number")return Number.isFinite(a)?a|0:void 0}
function ye(a){var b=0;b=b===void 0?0:b;if(!ue(a))throw yd("int64");var c=typeof a;switch(b){case 4096:switch(c){case "string":return ze(a);case "bigint":return String(BigInt.asIntN(64,a));default:return Ae(a)}case 8192:switch(c){case "string":return b=Math.trunc(Number(a)),Number.isSafeInteger(b)?a=ce(b):(b=a.indexOf("."),b!==-1&&(a=a.substring(0,b)),a=zd()?ce(BigInt.asIntN(64,BigInt(a))):ce(Be(a))),a;case "bigint":return ce(BigInt.asIntN(64,a));default:return Number.isSafeInteger(a)?ce(Ce(a)):ce(Ae(a))}case 0:switch(c){case "string":return ze(a);
case "bigint":return ce(BigInt.asIntN(64,a));default:return Ce(a)}default:return Bb(b,"Unknown format requested type for int64")}}
function De(a){return a==null?a:ye(a)}
function Ee(a){return a[0]==="-"?a.length<20?!0:a.length===20&&Number(a.substring(0,7))>-922337:a.length<19?!0:a.length===19&&Number(a.substring(0,6))<922337}
function Be(a){a.indexOf(".");if(Ee(a))return a;if(a.length<16)me(Number(a));else if(zd())a=BigInt(a),je=Number(a&BigInt(4294967295))>>>0,ke=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");ke=je=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),ke*=1E6,je=je*1E6+d,je>=4294967296&&(ke+=Math.trunc(je/4294967296),ke>>>=0,je>>>=0);b&&(b=z(ne(je,ke)),a=b.next().value,b=b.next().value,je=a,ke=b)}return qe()}
function Ce(a){ue(a);a=Math.trunc(a);if(!Number.isSafeInteger(a)){me(a);var b=je,c=ke;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);var d=c*4294967296+(b>>>0);b=Number.isSafeInteger(d)?d:oe(b,c);a=typeof b==="number"?a?-b:b:a?"-"+b:b}return a}
function Ae(a){ue(a);a=Math.trunc(a);if(Number.isSafeInteger(a))a=String(a);else{var b=String(a);Ee(b)?a=b:(me(a),a=qe())}return a}
function ze(a){ue(a);var b=Math.trunc(Number(a));if(Number.isSafeInteger(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Be(a)}
function Fe(a){if(a==null)return a;if(typeof a==="bigint")return ie(a)?a=Number(a):(a=BigInt.asIntN(64,a),a=ie(a)?Number(a):String(a)),a;if(ue(a))return typeof a==="number"?Ce(a):ze(a)}
function Ge(a){if(typeof a!=="string")throw Error();return a}
function He(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Ie(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+re(b)+" but got "+(a&&re(a.constructor)));}
function Je(a,b,c){if(a!=null&&typeof a==="object"&&a.Gc===Md)return a;if(Array.isArray(a)){var d=Hd(a),e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&Jd(a,e);return new b(a)}}
;function Ke(a){Le===void 0&&(Le=typeof Proxy==="function"?Me(Proxy):null);var b;(b=!Le)||(Ne===void 0&&(Ne=typeof WeakMap==="function"?Me(WeakMap):null),b=!Ne);if(b)return a;if(b=Oe(a))return b;if(Math.random()>.01)return a;Pe(a);b=new Le(a,{set:function(c,d,e){Qe();c[d]=e;return!0}});
Re(a,b);return b}
function Qe(){xd()}
var Se=void 0,Te=void 0;function Oe(a){var b;return(b=Se)==null?void 0:b.get(a)}
function Ue(a){var b;return((b=Te)==null?void 0:b.get(a))||a}
function Re(a,b){(Se||(Se=new Ne)).set(a,b);(Te||(Te=new Ne)).set(b,a)}
var Le=void 0,Ne=void 0;function Me(a){try{return a.toString().indexOf("[native code]")!==-1?a:null}catch(b){return null}}
var Ve=void 0;function Pe(a){if(Ve===void 0){var b=new Le([],{});Ve=Array.prototype.concat.call([],b).length===1}Ve&&typeof Symbol==="function"&&Symbol.isConcatSpreadable&&(a[Symbol.isConcatSpreadable]=!0)}
;var We;function Xe(a,b){Hd(b);We=b;a=new a(b);We=void 0;return a}
function K(a,b,c){var d=d!=null?d:0;a==null&&(a=We);We=void 0;if(a==null){var e=96;c?(a=[c],e|=512):a=[];b&&(e=e&-33521665|(b&1023)<<15)}else{if(!Array.isArray(a))throw Error("narr");e=Hd(a);if(e&2048)throw Error("farr");if(e&64)return a;d===1||d===2||(e|=64);if(c&&(e|=512,c!==a[0]))throw Error("mid");a:{c=a;if(d=c.length){var f=d-1;if(Pd(c[f])){e|=256;b=f-(+!!(e&512)-1);if(b>=1024)throw Error("pvtlmt");e=e&-33521665|(b&1023)<<15;break a}}if(b){b=Math.max(b,d-(+!!(e&512)-1));if(b>1024)throw Error("spvt");
e=e&-33521665|(b&1023)<<15}}}Jd(a,e);return a}
;function Ye(a,b){return Ze(b)}
function Ze(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "bigint":return ie(a)?Number(a):String(a);case "boolean":return a?1:0;case "object":if(a)if(Array.isArray(a)){if(Qd(a))return}else{if(rd(a))return nd(a);if(a instanceof td){var b=a.h;return b==null?"":typeof b==="string"?b:a.h=nd(b)}}}return a}
;function $e(a,b,c){a=Ad(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function af(a,b,c,d,e){if(a!=null){if(Array.isArray(a))a=Qd(a)?void 0:e&&Hd(a)&2?a:bf(a,b,c,d!==void 0,e);else if(Pd(a)){var f={},g;for(g in a)f[g]=af(a[g],b,c,d,e);a=f}else a=b(a,d);return a}}
function bf(a,b,c,d,e){var f=d||c?Hd(a):0;d=d?!!(f&32):void 0;a=Ad(a);for(var g=0;g<a.length;g++)a[g]=af(a[g],b,c,d,e);c&&c(f,a);return a}
function cf(a){return a.Gc===Md?a.toJSON():Ze(a)}
;function df(a,b,c){c=c===void 0?Ld:c;if(a!=null){if(ld&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=Hd(a);if(d&2)return a;b&&(b=d===0||!!(d&32)&&!(d&64||!(d&16)));return b?(Jd(a,(d|34)&-12293),a):bf(a,df,d&4?Ld:c,!0,!0)}a.Gc===Md&&(c=a.G,d=Id(c),a=d&2?a:Xe(a.constructor,ef(c,d,!0)));return a}}
function ef(a,b,c){var d=c||b&2?Ld:Kd,e=!!(b&32);a=$e(a,b,function(f){return df(f,e,d)});
Gd(a,32|(c?2:0));return a}
function ff(a){var b=a.G,c=Id(b);return c&2?Xe(a.constructor,ef(b,c,!1)):a}
;function gf(a,b){a=a.G;return hf(a,Id(a),b)}
function jf(a,b,c,d){b=d+(+!!(b&512)-1);if(!(b<0||b>=a.length||b>=c))return a[b]}
function hf(a,b,c,d){if(c===-1)return null;var e=b>>15&1023||536870912;if(c>=e){if(b&256)return a[a.length-1][c]}else{var f=a.length;if(d&&b&256&&(d=a[f-1][c],d!=null)){if(jf(a,b,e,c)&&Ed!=null){var g;a=(g=wd)!=null?g:wd={};g=a[Ed]||0;g>=4||(a[Ed]=g+1,xd())}return d}return jf(a,b,e,c)}}
function kf(a,b,c){var d=a.G,e=Id(d);Td(e);lf(d,e,b,c);return a}
function lf(a,b,c,d){Pd(d);var e=b>>15&1023||536870912;if(c>=e){var f=b;if(b&256)var g=a[a.length-1];else{if(d==null)return f;g=a[e+(+!!(b&512)-1)]={};f|=256}g[c]=d;c<e&&(a[c+(+!!(b&512)-1)]=void 0);f!==b&&Jd(a,f);return f}a[c+(+!!(b&512)-1)]=d;b&256&&(a=a[a.length-1],c in a&&delete a[c]);return b}
function mf(a){return nf(a,of,11,!1)!==void 0}
function pf(a){return!!(2&a)&&!!(4&a)||!!(2048&a)}
function qf(a,b,c){var d=a.G,e=Id(d);Td(e);if(b==null)return lf(d,e,3),a;b=Ue(b);if(!Array.isArray(b))throw yd();var f=Hd(b),g=f,h=!!(4&f),k=pf(f),l=k||Object.isFrozen(b);k||(f=0);l||(b=Ad(b),g=0,f=rf(f,e),f=sf(f,e,!0),l=!1);f|=21;k=4&f?4096&f?4096:8192&f?8192:0:void 0;k=k!=null?k:0;if(!h)for(h=0;h<b.length;h++){var m=b[h],n=c(m,k);Object.is(m,n)||(l&&(b=Ad(b),g=0,f=rf(f,e),f=sf(f,e,!0),l=!1),b[h]=n)}f!==g&&(l&&(b=Ad(b),f=rf(f,e),f=sf(f,e,!0)),Jd(b,f));lf(d,e,3,b);return a}
function tf(a,b,c,d){a=a.G;var e=Id(a);Td(e);if(d==null){var f=uf(a);if(vf(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=uf(a);var g=vf(f,a,e,c);g!==b&&(g&&(e=lf(a,e,g)),f.set(c,b))}lf(a,e,b,d)}
function uf(a){if(Bd){var b;return(b=a[Fd])!=null?b:a[Fd]=new Map}if(Fd in a)return a[Fd];b=new Map;Object.defineProperty(a,Fd,{value:b});return b}
function vf(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];hf(b,c,g)!=null&&(e!==0&&(c=lf(b,c,e)),e=g)}a.set(d,e);return e}
function nf(a,b,c,d){a=a.G;var e=Id(a);d=hf(a,e,c,d);b=Je(d,b,e);b!==d&&b!=null&&lf(a,e,c,b);return b}
function wf(a,b,c,d){b=nf(a,b,c,d===void 0?!1:d);if(b==null)return b;a=a.G;d=Id(a);if(!(d&2)){var e=ff(b);e!==b&&(b=e,lf(a,d,c,b))}return b}
function lc(a,b,c){var d=void 0===Ud?2:Mc?4:5;var e=Id(a.G),f=e,g=!(2&e);a=a.G;d=(e=!!(2&f))?1:d;g&&(g=!e);e=hf(a,f,c);e=Array.isArray(e)?e:Rd;var h=Hd(e),k=!!(4&h);if(!k){var l=h;l===0&&(l=rf(l,f));h=e;l|=1;var m=f,n=!!(2&l);n&&(m|=2);for(var p=!n,t=!0,v=0,x=0;v<h.length;v++){var y=Je(h[v],b,m);if(y instanceof b){if(!n){var G=!!(Hd(y.G)&2);p&&(p=!G);t&&(t=G)}h[x++]=y}}x<v&&(h.length=x);l|=4;l=t?l|16:l&-17;l=p?l|8:l&-9;Jd(h,l);n&&Object.freeze(h);h=l}if(g&&!(8&h||!e.length&&(d===1||d===4&&32&h))){pf(h)&&
(e=Ad(e),h=rf(h,f),f=lf(a,f,c,e));b=e;g=h;for(h=0;h<b.length;h++)l=b[h],m=ff(l),l!==m&&(b[h]=m);g|=8;g=b.length?g&-17:g|16;Jd(b,g);h=g}var I;if(d===1||d===4&&32&h){if(!pf(h)){f=h;var O=!!(32&h);h|=!e.length||16&h&&(!k||O)?2:2048;h!==f&&Jd(e,h);Object.freeze(e)}}else k=d!==5?!1:!!(32&h)||pf(h)||!!Oe(e),(d===2||k)&&pf(h)&&(e=Ad(e),h=rf(h,f),h=sf(h,f,!1),Jd(e,h),f=lf(a,f,c,e)),pf(h)||(c=h,h=sf(h,f,!1),h!==c&&Jd(e,h)),k?I=Ke(e):d===2&&((O=Se)==null||O.delete(e));return I||e}
function xf(a,b,c,d){d!=null?Ie(d,b):d=void 0;return kf(a,c,d)}
function yf(a,b,c,d){var e=a.G,f=Id(e);Td(f);if(d==null)return lf(e,f,c),a;d=Ue(d);if(!Array.isArray(d))throw yd();for(var g=Hd(d),h=g,k=pf(g),l=k||Object.isFrozen(d),m=!l&&!0,n=!0,p=!0,t=0;t<d.length;t++){var v=d[t];Ie(v,b);k||(v=!!(Hd(v.G)&2),n&&(n=!v),p&&(p=v))}k||(g=n?13:5,g=p?g|16:g&-17);if(m||l&&g!==h)d=Ad(d),h=0,g=rf(g,f),g=sf(g,f,!0);g!==h&&Jd(d,g);lf(e,f,c,d);return a}
function rf(a,b){a=(2&b?a|2:a&-3)|32;return a&=-2049}
function sf(a,b,c){32&b&&c||(a&=-33);return a}
function zf(a){a=gf(a,1);var b=b===void 0?!1:b;var c=typeof a;b=a==null?a:c==="bigint"?String(BigInt.asIntN(64,a)):ue(a)?c==="string"?ze(a):b?Ae(a):Ce(a):void 0;return b}
function Af(a,b){return a!=null?a:b}
function Bf(a){var b=b===void 0?!1:b;a=gf(a,4);return Af(a==null||typeof a==="boolean"?a:typeof a==="number"?!!a:void 0,b)}
function nc(a,b,c){c=c===void 0?0:c;return Af(xe(gf(a,b)),c)}
function Cf(a,b){var c=c===void 0?"":c;a=gf(a,b);return Af(a==null||typeof a==="string"?a:void 0,c)}
function Df(a){var b=0;b=b===void 0?0:b;a=gf(a,1);a=a==null?a:Number.isFinite(a)?a|0:void 0;return Af(a,b)}
function Ef(a,b,c){return kf(a,b,He(c))}
function Ff(a,b,c){if(c!=null){if(!Number.isFinite(c))throw yd("enum");c|=0}return kf(a,b,c)}
;function Gf(a){return a}
function Hf(a){return a}
function If(a,b,c,d){return Jf(a,b,c,d,Kf,Lf)}
function Mf(a,b,c,d){return Jf(a,b,c,d,Nf,Of)}
function Jf(a,b,c,d,e,f){if(!c.length&&!d)return 0;for(var g=0,h=0,k=0,l=0,m=0,n=c.length-1;n>=0;n--){var p=c[n];d&&n===c.length-1&&p===d||(l++,p!=null&&k++)}if(d)for(var t in d)n=+t,isNaN(n)||(m+=Pf(n),h++,n>g&&(g=n));l=e(l,k)+f(h,g,m);t=k;n=h;p=g;for(var v=m,x=c.length-1;x>=0;x--){var y=c[x];if(!(y==null||d&&x===c.length-1&&y===d)){y=x-b;var G=e(y,t)+f(n,p,v);G<l&&(a=1+y,l=G);n++;t--;v+=Pf(y);p=Math.max(p,y)}}b=e(0,0)+f(n,p,v);b<l&&(a=0,l=b);if(d){n=h;p=g;v=m;t=k;for(var I in d)d=+I,isNaN(d)||d>=
1024||(n--,t++,v-=I.length,g=e(d,t)+f(n,p,v),g<l&&(a=1+d,l=g))}return a}
function Of(a,b,c){return c+a*3+(a>1?a-1:0)}
function Nf(a,b){return(a>1?a-1:0)+(a-b)*4}
function Lf(a,b){return a==0?0:9*Math.max(1<<32-Math.clz32(a+a/2-1),4)<=b?a==0?0:a<4?100+(a-1)*16:a<6?148+(a-4)*16:a<12?244+(a-6)*16:a<22?436+(a-12)*19:a<44?820+(a-22)*17:52+32*a:40+4*b}
function Kf(a){return 40+4*a}
function Pf(a){return a>=100?a>=1E4?Math.ceil(Math.log10(1+a)):a<1E3?3:4:a<10?1:2}
;var Qf,Rf;function L(a,b,c){this.G=K(a,b,c)}
r=L.prototype;r.toJSON=function(){return Sf(this)};
r.serialize=function(a){try{return Rf=!0,a&&(Qf=a===Hf||a!==Gf&&a!==If&&a!==Mf?Hf:a),JSON.stringify(Sf(this),Ye)}finally{a&&(Qf=void 0),Rf=!1}};
function Tf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");Gd(b,32);return Xe(a,b)}
r.clone=function(){var a=this.G,b=Id(a);return Xe(this.constructor,ef(a,b,!1))};
r.Gc=Md;r.toString=function(){try{return Rf=!0,Sf(this).toString()}finally{Rf=!1}};
function Sf(a){var b;Rf?b=a.G:b=bf(a.G,cf,void 0,void 0,!1);var c=!Rf,d=Id(c?a.G:b);if(a=b.length){var e=b[a-1],f=Pd(e);f?a--:e=void 0;var g=+!!(d&512)-1,h=a-g;d=!!Qf&&!(d&512);var k,l=(k=Qf)!=null?k:Hf;k=d?l(h,g,b,e):h;d=(h=d&&h!==k)?Array.prototype.slice.call(b,0,a):b;if(f||h){b:{var m=d;var n=e;var p;f=!1;if(h)for(l=Math.max(0,k+g);l<m.length;l++){var t=m[l],v=l-g;t==null||Qd(t)||Od(t)&&t.size===0||(f=m[l]=void 0,((f=p)!=null?f:p={})[v]=t,f=!0)}if(n)for(var x in n)if(l=+x,isNaN(l))l=void 0,((l=
p)!=null?l:p={})[x]=n[x];else if(t=n[x],Array.isArray(t)&&(Qd(t)||Od(t)&&t.size===0)&&(t=null),t==null&&(f=!0),h&&l<k){f=!0;t=l+g;for(v=m.length;v<=t;v++)m.push(void 0);m[t]=n[l]}else t!=null&&(l=void 0,((l=p)!=null?l:p={})[x]=t);f||(p=n);if(p)for(var y in p){n=p;break b}n=null}m=n==null?e!=null:n!==e}h&&(a=d.length);for(;a>0;a--){p=d[a-1];if(!(p==null||Qd(p)||Od(p)&&p.size===0))break;var G=!0}if(d!==b||m||G){if(!h&&!c)d=Array.prototype.slice.call(d,0,a);else if(G||m||n)d.length=a;n&&d.push(n)}G=
d}else G=b;return G}
;function Uf(a){return function(b){return Tf(a,b)}}
;function Vf(a){this.G=K(a)}
w(Vf,L);function Wf(a,b){return qf(a,b,ve)}
;function Xf(a){this.G=K(a)}
w(Xf,L);var Yf=[1,2,3];function Zf(a){this.G=K(a)}
w(Zf,L);var $f=[1,2,3];function ag(a){this.G=K(a)}
w(ag,L);function bg(a){this.G=K(a)}
w(bg,L);function cg(a){this.G=K(a)}
w(cg,L);function dg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function eg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var p=g,t=0;t<64;t+=4)p[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=p[t-3]^p[t-8]^p[t-14]^p[t-16],p[t]=(n<<1|n>>>31)&4294967295;n=e[0];var v=e[1],x=e[2],y=e[3],G=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var I=y^v&(x^y);var O=1518500249}else I=v^x^y,O=1859775393;else t<60?(I=v&x|y&(v|x),O=2400959708):(I=v^x^y,O=3395469782);I=((n<<5|n>>>27)&4294967295)+I+G+O+p[t]&4294967295;G=y;y=x;x=(v<<30|v>>>2)&4294967295;v=n;n=I}e[0]=e[0]+n&4294967295;e[1]=e[1]+v&4294967295;e[2]=
e[2]+x&4294967295;e[3]=e[3]+y&4294967295;e[4]=e[4]+G&4294967295}
function c(n,p){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],v=0,x=n.length;v<x;++v)t.push(n.charCodeAt(v));n=t}p||(p=n.length);t=0;if(l==0)for(;t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<p;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],p=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=p&255,p>>>=8;b(f);for(t=p=0;t<5;t++)for(var v=24;v>=0;v-=8)n[p++]=e[t]>>v&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Ud:function(){for(var n=d(),p="",t=0;t<n.length;t++)p+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return p}}}
;function fg(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,gg(dg(d),a,c||null)].join(" "):null}
function gg(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Kb(d,function(h){e.push(h)}),hg(e.join(" "));
var f=[],g=[];Kb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Kb(d,function(h){e.push(h)});
a=hg(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function hg(a){var b=eg();b.update(a);return b.Ud().toLowerCase()}
;var ig={};function jg(a){this.h=a||{cookie:""}}
r=jg.prototype;r.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Lb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
r.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.Ne;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Lb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
r.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=bb(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
r.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Lb:0,path:b,domain:c});return d};
r.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=bb(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var kg=new jg(typeof document=="undefined"?null:document);function lg(a){return!!ig.FPA_SAMESITE_PHASE2_MOD||!(a===void 0||!a)}
function mg(a){a=a===void 0?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;lg(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if(typeof document!=="undefined"){var c=new jg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID");lg(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function ng(a,b,c,d){(a=C[a])||typeof document==="undefined"||(a=(new jg(document)).get(b));return a?fg(a,c,d):null}
function og(a,b){b=b===void 0?!1:b;var c=dg(String(C.location.href)),d=[];if(mg(b)){c=c.indexOf("https:")==0||c.indexOf("chrome-extension:")==0||c.indexOf("chrome-untrusted://new-tab-page")==0||c.indexOf("moz-extension:")==0;var e=c?C.__SAPISID:C.__APISID;e||typeof document==="undefined"||(e=new jg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?fg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&lg(b)&&((b=ng("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),
(a=ng("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return d.length==0?null:d.join(" ")}
;function pg(){}
pg.prototype.compress=function(a){var b,c,d,e;return A(function(f){switch(f.h){case 1:return b=new CompressionStream("gzip"),c=(new Response(b.readable)).arrayBuffer(),d=b.writable.getWriter(),f.yield(d.write((new TextEncoder).encode(a)),2);case 2:return f.yield(d.close(),3);case 3:return e=Uint8Array,f.yield(c,4);case 4:return f.return(new e(f.i))}})};
pg.prototype.isSupported=function(a){return a<1024?!1:typeof CompressionStream!=="undefined"};function qg(a){this.G=K(a)}
w(qg,L);function rg(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return Ya()};
this.i=this.h()}
rg.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
rg.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
rg.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
rg.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function sg(a){this.G=K(a)}
w(sg,L);function tg(a){this.G=K(a)}
w(tg,L);function ug(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
r=ug.prototype;r.clone=function(){return new ug(this.x,this.y)};
r.equals=function(a){return a instanceof ug&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
r.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
r.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
r.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
r.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function vg(a,b){this.width=a;this.height=b}
r=vg.prototype;r.clone=function(){return new vg(this.width,this.height)};
r.aspectRatio=function(){return this.width/this.height};
r.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
r.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
r.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
r.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function wg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function xg(a){var b=yg,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function zg(a){for(var b in a)return!1;return!0}
function Ag(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Bg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function Cg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Dg(a){var b={},c;for(c in a)b[c]=a[c];return b}
function Eg(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Eg(a[c]);return b}
var Fg="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Gg(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Fg.length;f++)c=Fg[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function Hg(a,b){this.h=a===Ig&&b||""}
Hg.prototype.toString=function(){return this.h};
var Ig={};new Hg(Ig,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Jg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function Kg(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function Lg(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Mg=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();function Ng(a){this.h=this.i=this.j=a}
Ng.prototype.reset=function(){this.h=this.i=this.j};
Ng.prototype.getValue=function(){return this.i};function Og(a){this.G=K(a)}
w(Og,L);Og.prototype.ec=function(){return Df(this)};function Pg(a){this.G=K(a)}
w(Pg,L);function Qg(a){this.G=K(a)}
w(Qg,L);function Rg(a,b){yf(a,Pg,1,b)}
;function of(a){this.G=K(a)}
w(of,L);var Sg=["platform","platformVersion","architecture","model","uaFullVersion"],Tg=new Qg,Ug=null;function Vg(a,b){b=b===void 0?Sg:b;if(!Ug){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new Pg;f=Ef(f,1,e.brand);return Ef(f,2,e.version)});
Rg(kf(Tg,2,se(a.mobile)),c);Ug=a.getHighEntropyValues(b)}var d=new Set(b);return Ug.then(function(e){var f=Tg.clone();d.has("platform")&&Ef(f,3,e.platform);d.has("platformVersion")&&Ef(f,4,e.platformVersion);d.has("architecture")&&Ef(f,5,e.architecture);d.has("model")&&Ef(f,6,e.model);d.has("uaFullVersion")&&Ef(f,7,e.uaFullVersion);return f}).catch(function(){return Tg.clone()})}
;function Wg(a){this.G=K(a)}
w(Wg,L);function Xg(a){this.G=K(a,4)}
w(Xg,L);function Yg(a){this.G=K(a,36)}
w(Yg,L);function ah(a){this.G=K(a,19)}
w(ah,L);ah.prototype.Ob=function(a){return Ff(this,2,a)};function bh(a){this.G=K(a,8)}
w(bh,L);var ch=Uf(bh);function dh(a){this.G=K(a)}
w(dh,L);var eh=new function(){this.ctor=dh;this.isRepeated=0;this.h=wf;this.defaultValue=void 0};function fh(a){F.call(this);var b=this;this.componentId="";this.j=[];this.ga="";this.pageId=null;this.ja=this.U=-1;this.B=this.experimentIds=null;this.R=this.u=0;this.ta=1;this.timeoutMillis=0;this.logSource=a.logSource;this.Hb=a.Hb||function(){};
this.i=new gh(a.logSource,a.Za);this.network=a.network;this.xb=a.xb||null;this.bufferSize=1E3;this.H=a.qf||null;this.sessionIndex=a.sessionIndex||null;this.Fb=a.Fb||!1;this.logger=null;this.withCredentials=!a.Yc;this.Za=a.Za||!1;this.Z=typeof URLSearchParams!=="undefined"&&!!(new URL(hh())).searchParams&&!!(new URL(hh())).searchParams.set;var c=Ff(new Wg,1,1);ih(this.i,c);this.o=new Ng(1E4);a=jh(this,a.Tc);this.h=new rg(this.o.getValue(),a);this.Y=new rg(6E5,a);this.Fb||this.Y.start();this.Za||(document.addEventListener("visibilitychange",
function(){document.visibilityState==="hidden"&&b.yc()}),document.addEventListener("pagehide",this.yc.bind(this)))}
w(fh,F);function jh(a,b){return a.Z?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
r=fh.prototype;r.aa=function(){this.yc();this.h.stop();this.Y.stop();F.prototype.aa.call(this)};
r.log=function(a){if(this.Z){a=a.clone();var b=this.ta++;a=kf(a,21,De(b));this.componentId&&Ef(a,26,this.componentId);if(zf(a)==null){var c=Date.now();b=a;c=Number.isFinite(c)?c.toString():"0";kf(b,1,De(c))}Fe(gf(a,15))==null&&kf(a,15,De((new Date).getTimezoneOffset()*60));this.experimentIds&&(b=a,c=this.experimentIds.clone(),xf(b,qg,16,c));b=this.j.length-this.bufferSize+1;b>0&&(this.j.splice(0,b),this.u+=b);this.j.push(a);this.Fb||this.h.enabled||this.h.start()}};
r.flush=function(a,b){var c=this;if(this.j.length===0)a&&a();else{var d=Date.now();if(this.ja>d&&this.U<d)b&&b("throttled");else{this.network&&(typeof this.network.ec==="function"?kh(this.i,this.network.ec()):kh(this.i,0));var e=lh(this.i,this.j,this.u,this.R,this.xb);d={};var f=this.Hb();f&&(d.Authorization=f);this.H||(this.H=hh());try{var g=(new URL(this.H)).toString()}catch(t){g=(new URL(this.H,window.location.origin)).toString()}g=new URL(g);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,
g.searchParams.set("authuser",this.sessionIndex));this.pageId&&(Object.defineProperty(d,"X-Goog-PageId",{value:this.pageId}),g.searchParams.set("pageId",this.pageId));if(f&&this.ga===f)b&&b("stale-auth-token");else{this.j=[];this.h.enabled&&this.h.stop();this.u=0;var h=e.serialize(),k;this.B&&this.B.isSupported(h.length)&&(k=this.B.compress(h));var l={url:g.toString(),body:h,Md:1,qc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},m=function(t){c.o.reset();
c.h.setInterval(c.o.getValue());if(t){var v=null;try{var x=JSON.stringify(JSON.parse(t.replace(")]}'\n","")));v=ch(x)}catch(y){}v&&(t=Number,x="-1",x=x===void 0?"0":x,x=Af(zf(v),x),t=t(x),t>0&&(c.U=Date.now(),c.ja=c.U+t),v=eh.ctor?eh.h(v,eh.ctor,175237375,!0):eh.h(v,175237375,null,!0),v=v===null?void 0:v)&&(v=nc(v,1,-1),v!==-1&&(c.o=new Ng(v<1?1:v),c.h.setInterval(c.o.getValue())))}a&&a();c.R=0},n=function(t,v){var x=lc(e,Yg,3);
var y=Fe(gf(e,14));y=y==null?void 0:y;var G=c.o;G.h=Math.min(3E5,G.h*2);G.i=Math.min(3E5,G.h+Math.round(.1*(Math.random()-.5)*2*G.h));c.h.setInterval(c.o.getValue());t===401&&f&&(c.ga=f);y&&(c.u+=y);v===void 0&&(v=c.isRetryable(t));v&&(c.j=x.concat(c.j),c.Fb||c.h.enabled||c.h.start());b&&b("net-send-failed",t);++c.R},p=function(){c.network&&c.network.send(l,m,n)};
k?k.then(function(t){l.qc["Content-Encoding"]="gzip";l.qc["Content-Type"]="application/binary";l.body=t;l.Md=2;p()},function(){p()}):p()}}}};
r.yc=function(){mh(this.i,!0);this.flush();mh(this.i,!1)};
r.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function hh(){return"https://play.google.com/log?format=json&hasfast=true"}
function gh(a,b){this.Za=b=b===void 0?!1:b;this.i=this.locale=null;this.h=new ah;Number.isInteger(a)&&this.h.Ob(a);b||(this.locale=document.documentElement.getAttribute("lang"));ih(this,new Wg)}
gh.prototype.Ob=function(a){this.h.Ob(a);return this};
function ih(a,b){xf(a.h,Wg,1,b);Df(b)||Ff(b,1,1);a.Za||(b=nh(a),Cf(b,5)||Ef(b,5,a.locale));a.i&&(b=nh(a),wf(b,Qg,9)||xf(b,Qg,9,a.i))}
function kh(a,b){mf(oh(a))&&(a=ph(a),Ff(a,1,b))}
function mh(a,b){mf(oh(a))&&(a=ph(a),kf(a,2,se(b)))}
function oh(a){return wf(a.h,Wg,1)}
function qh(a){var b=b===void 0?Sg:b;var c=a.Za?void 0:window;c?Vg(c,b).then(function(d){a.i=d;d=nh(a);xf(d,Qg,9,a.i);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function nh(a){a=oh(a);var b=wf(a,of,11);b||(b=new of,xf(a,of,11,b));return b}
function ph(a){a=nh(a);var b=wf(a,Og,10);b||(b=new Og,kf(b,2,se(!1)),xf(a,Og,10,b));return b}
function lh(a,b,c,d,e){var f=0,g=0;c=c===void 0?0:c;f=f===void 0?0:f;g=g===void 0?0:g;d=d===void 0?0:d;if(mf(oh(a))){var h=ph(a);kf(h,3,we(d))}mf(oh(a))&&(d=ph(a),kf(d,4,we(f)));mf(oh(a))&&(f=ph(a),kf(f,5,we(g)));a=a.h.clone();g=Date.now().toString();a=kf(a,4,De(g));b=b.slice();b=yf(a,Yg,3,b);e&&(a=new sg,e=kf(a,13,we(e)),a=new tg,e=xf(a,sg,2,e),a=new Xg,e=xf(a,tg,1,e),e=Ff(e,2,9),xf(b,Xg,18,e));c&&kf(b,14,De(c));return b}
;function rh(){this.Hd=typeof AbortController!=="undefined"}
rh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,p,t;return A(function(v){switch(v.h){case 1:return f=(e=d.Hd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,ya(v,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.qc)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),v.yield(fetch(a.url,g),5);case 5:h=v.i;if(h.status!==200){(k=c)==null||k(h.status);v.F(3);break}if((l=b)==null){v.F(7);break}return v.yield(h.text(),8);case 8:l(v.i);case 7:case 3:v.R=[v.j];v.o=0;v.D=0;clearTimeout(f);Aa(v);break;case 2:m=za(v);switch((n=m)==null?void 0:n.name){case "AbortError":(p=c)==null||p(408);break;default:(t=c)==null||t(400)}v.F(3)}})};
rh.prototype.ec=function(){return 4};function sh(a,b){F.call(this);this.logSource=a;this.sessionIndex=b;this.j="https://play.google.com/log?format=json&hasfast=true";this.i=null;this.o=!1;this.network=null;this.componentId="";this.pageId=this.h=this.xb=null}
w(sh,F);function th(a,b){a.i=b;return a}
function uh(a,b){a.network=b;return a}
function vh(a,b){a.h=b}
sh.prototype.Yc=function(){this.u=!0;return this};
function wh(a){a.network||(a.network=new rh);var b=new fh({logSource:a.logSource,Hb:a.Hb?a.Hb:og,sessionIndex:a.sessionIndex,qf:a.j,Za:a.o,Fb:!1,Yc:a.u,Tc:a.Tc,network:a.network});rc(a,b);if(a.i){var c=a.i,d=nh(b.i);Ef(d,7,c)}Math.random()<.01&&(b.B=new pg);a.componentId&&(b.componentId=a.componentId);a.xb&&(b.xb=a.xb);a.pageId&&(b.pageId=a.pageId);a.h&&((d=a.h)?(b.experimentIds||(b.experimentIds=new qg),c=b.experimentIds,d=d.serialize(),Ef(c,4,d)):b.experimentIds&&kf(b.experimentIds,4));qh(b.i);
a.network.Ob&&a.network.Ob(a.logSource);a.network.Ye&&a.network.Ye(b);return b}
;function xh(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;F.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new sh(a,"0"),a.componentId=b,rc(this,a),c!==""&&(a.j=c),d&&(a.o=!0),e&&th(a,e),g&&uh(a,g),b=wh(a));this.h=b}
w(xh,F);
xh.prototype.flush=function(a){var b=a||[];if(b.length){a=new cg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new bg;f=Ef(f,1,e.i);var g=yh(e);f=qf(f,g,Ge);g=[];var h=[];for(var k=z(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.zc(l)||[],p=[],t=0;t<n.length;t++){var v=n[t],x=v&&v.h;v=new Zf;switch(m){case 3:x=Number(x);Number.isFinite(x)&&tf(v,1,$f,De(x));break;case 2:x=Number(x);if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+
": "+x);tf(v,2,$f,x)}p.push(v)}m=p;for(n=0;n<m.length;n++){p=m[n];t=new ag;p=xf(t,Zf,2,p);t=l;v=[];x=zh(e);for(var y=0;y<x.length;y++){var G=x[y],I=t[y],O=new Xf;switch(G){case 3:tf(O,1,Yf,He(String(I)));break;case 2:G=Number(I);Number.isFinite(G)&&tf(O,2,Yf,we(G));break;case 1:tf(O,3,Yf,se(I==="true"))}v.push(O)}yf(p,Xf,1,v);g.push(p)}}yf(f,ag,4,g);c.push(f);e.clear()}yf(a,bg,1,c);b=this.h;if(a instanceof Yg)b.log(a);else try{var T=new Yg,Ja=a.serialize();var cb=Ef(T,8,Ja);b.log(cb)}catch(ca){}this.h.flush()}};function Ah(a){this.h=a}
;function Bh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function zh(a){return a.fields.map(function(b){return b.fieldType})}
function yh(a){return a.fields.map(function(b){return b.fieldName})}
r=Bh.prototype;r.Id=function(a){var b=B.apply(1,arguments),c=this.zc(b);c?c.push(new Ah(a)):this.td(a,b)};
r.td=function(a){var b=this.Sc(B.apply(1,arguments));this.h.set(b,[new Ah(a)])};
r.zc=function(){var a=this.Sc(B.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
r.ee=function(){var a=this.zc(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
r.clear=function(){this.h.clear()};
r.Sc=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function Ch(a,b){Bh.call(this,a,3,b)}
w(Ch,Bh);Ch.prototype.j=function(a){var b=B.apply(1,arguments),c=0,d=this.ee(b);d&&(c=d.h);this.td(c+a,b)};function Dh(a,b){Bh.call(this,a,2,b)}
w(Dh,Bh);Dh.prototype.record=function(a){this.Id(a,B.apply(1,arguments))};function Eh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Eh.prototype.stopPropagation=function(){this.j=!0};
Eh.prototype.preventDefault=function(){this.defaultPrevented=!0};function Fh(a,b){Eh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Za(Fh,Eh);
Fh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&Fh.Aa.preventDefault.call(this)};
Fh.prototype.stopPropagation=function(){Fh.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Fh.prototype.preventDefault=function(){Fh.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Gh="closure_listenable_"+(Math.random()*1E6|0);var Hh=0;function Ih(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.fc=e;this.key=++Hh;this.Nb=this.Xb=!1}
function Jh(a){a.Nb=!0;a.listener=null;a.proxy=null;a.src=null;a.fc=null}
;function Kh(a){this.src=a;this.listeners={};this.h=0}
Kh.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Lh(a,b,d,e);g>-1?(b=a[g],c||(b.Xb=!1)):(b=new Ih(b,this.src,f,!!d,e),b.Xb=c,a.push(b));return b};
Kh.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Lh(e,b,c,d);return b>-1?(Jh(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function Mh(a,b){var c=b.type;c in a.listeners&&Pb(a.listeners[c],b)&&(Jh(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function Lh(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Nb&&f.listener==b&&f.capture==!!c&&f.fc==d)return e}return-1}
;var Nh="closure_lm_"+(Math.random()*1E6|0),Oh={},Ph=0;function Qh(a,b,c,d,e){if(d&&d.once)Rh(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Qh(a,b[f],c,d,e);else c=Sh(c),a&&a[Gh]?a.listen(b,c,Qa(d)?!!d.capture:!!d,e):Th(a,b,c,!1,d,e)}
function Th(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Qa(e)?!!e.capture:!!e,h=Uh(a);h||(a[Nh]=h=new Kh(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Vh();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Mg||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Wh(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ph++}}
function Vh(){function a(c){return b.call(a.src,a.listener,c)}
var b=Xh;return a}
function Rh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Rh(a,b[f],c,d,e);else c=Sh(c),a&&a[Gh]?a.h.add(String(b),c,!0,Qa(d)?!!d.capture:!!d,e):Th(a,b,c,!0,d,e)}
function Yh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Yh(a,b[f],c,d,e);else(d=Qa(d)?!!d.capture:!!d,c=Sh(c),a&&a[Gh])?a.h.remove(String(b),c,d,e):a&&(a=Uh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Lh(b,c,d,e)),(c=a>-1?b[a]:null)&&Zh(c))}
function Zh(a){if(typeof a!=="number"&&a&&!a.Nb){var b=a.src;if(b&&b[Gh])Mh(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Wh(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ph--;(c=Uh(b))?(Mh(c,a),c.h==0&&(c.src=null,b[Nh]=null)):Jh(a)}}}
function Wh(a){return a in Oh?Oh[a]:Oh[a]="on"+a}
function Xh(a,b){if(a.Nb)a=!0;else{b=new Fh(b,this);var c=a.listener,d=a.fc||a.src;a.Xb&&Zh(a);a=c.call(d,b)}return a}
function Uh(a){a=a[Nh];return a instanceof Kh?a:null}
var $h="__closure_events_fn_"+(Math.random()*1E9>>>0);function Sh(a){if(typeof a==="function")return a;a[$h]||(a[$h]=function(b){return a.handleEvent(b)});
return a[$h]}
;function ai(){F.call(this);this.h=new Kh(this);this.ta=this;this.Z=null}
Za(ai,F);ai.prototype[Gh]=!0;r=ai.prototype;r.addEventListener=function(a,b,c,d){Qh(this,a,b,c,d)};
r.removeEventListener=function(a,b,c,d){Yh(this,a,b,c,d)};
function bi(a,b){var c=a.Z;if(c){var d=[];for(var e=1;c;c=c.Z)d.push(c),++e}a=a.ta;c=b.type||b;typeof b==="string"?b=new Eh(b,a):b instanceof Eh?b.target=b.target||a:(e=b,b=new Eh(c,a),Gg(b,e));e=!0;var f;if(d)for(f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=ci(g,c,!0,b)&&e}b.j||(g=b.h=a,e=ci(g,c,!0,b)&&e,b.j||(e=ci(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=ci(g,c,!1,b)&&e}
r.aa=function(){ai.Aa.aa.call(this);this.removeAllListeners();this.Z=null};
r.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
r.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,Jh(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function ci(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Nb&&g.capture==c){var h=g.listener,k=g.fc||g.src;g.Xb&&Mh(a.h,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;var di=typeof AsyncContext!=="undefined"&&typeof AsyncContext.Snapshot==="function"?function(a){return a&&AsyncContext.Snapshot.wrap(a)}:function(a){return a};function ei(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
ei.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function fi(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function gi(){this.i=this.h=null}
gi.prototype.add=function(a,b){var c=hi.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
gi.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var hi=new ei(function(){return new ii},function(a){return a.reset()});
function ii(){this.next=this.scope=this.h=null}
ii.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
ii.prototype.reset=function(){this.next=this.scope=this.h=null};var ji,ki=!1,li=new gi;function mi(a,b){ji||ni();ki||(ji(),ki=!0);li.add(a,b)}
function ni(){var a=Promise.resolve(void 0);ji=function(){a.then(oi)}}
function oi(){for(var a;a=li.remove();){try{a.h.call(a.scope)}catch(b){Kc(b)}fi(hi,a)}ki=!1}
;function pi(){}
function qi(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function ri(a){this.h=0;this.B=void 0;this.o=this.i=this.j=null;this.D=this.u=!1;if(a!=pi)try{var b=this;a.call(void 0,function(c){si(b,2,c)},function(c){si(b,3,c)})}catch(c){si(this,3,c)}}
function ti(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
ti.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var ui=new ei(function(){return new ti},function(a){a.reset()});
function vi(a,b,c){var d=ui.get();d.i=a;d.h=b;d.context=c;return d}
function wi(a){return new ri(function(b,c){c(a)})}
ri.prototype.then=function(a,b,c){return xi(this,di(typeof a==="function"?a:null),di(typeof b==="function"?b:null),c)};
ri.prototype.$goog_Thenable=!0;r=ri.prototype;r.uc=function(a,b){return xi(this,null,di(a),b)};
r.catch=ri.prototype.uc;r.cancel=function(a){if(this.h==0){var b=new yi(a);mi(function(){zi(this,b)},this)}};
function zi(a,b){if(a.h==0)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.h==0&&d==1?zi(c,b):(f?(d=f,d.next==c.o&&(c.o=d),d.next=d.next.next):Ai(c),Bi(c,e,3,b)))}a.j=null}else si(a,3,b)}
function Ci(a,b){a.i||a.h!=2&&a.h!=3||Di(a);a.o?a.o.next=b:a.i=b;a.o=b}
function xi(a,b,c,d){var e=vi(null,null,null);e.child=new ri(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof yi?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;Ci(a,e);return e.child}
r.nf=function(a){this.h=0;si(this,2,a)};
r.pf=function(a){this.h=0;si(this,3,a)};
function si(a,b,c){if(a.h==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.nf,f=a.pf;if(d instanceof ri){Ci(d,vi(e||pi,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Qa(d))try{var k=d.then;if(typeof k==="function"){Ei(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.B=c,a.h=b,a.j=null,Di(a),b!=3||c instanceof yi||Fi(a,c))}}
function Ei(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Di(a){a.u||(a.u=!0,mi(a.Zd,a))}
function Ai(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.o=null);return b}
r.Zd=function(){for(var a;a=Ai(this);)Bi(this,a,this.h,this.B);this.u=!1};
function Bi(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.D;a=a.j)a.D=!1;if(b.child)b.child.j=null,Gi(b,c,d);else try{b.j?b.i.call(b.context):Gi(b,c,d)}catch(e){Hi.call(null,e)}fi(ui,b)}
function Gi(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function Fi(a,b){a.D=!0;mi(function(){a.D&&Hi.call(null,b)})}
var Hi=Kc;function yi(a){$a.call(this,a)}
Za(yi,$a);yi.prototype.name="cancel";function Ii(a,b){ai.call(this);this.j=a||1;this.i=b||C;this.o=Wa(this.kf,this);this.u=Ya()}
Za(Ii,ai);r=Ii.prototype;r.enabled=!1;r.Da=null;r.setInterval=function(a){this.j=a;this.Da&&this.enabled?(this.stop(),this.start()):this.Da&&this.stop()};
r.kf=function(){if(this.enabled){var a=Ya()-this.u;a>0&&a<this.j*.8?this.Da=this.i.setTimeout(this.o,this.j-a):(this.Da&&(this.i.clearTimeout(this.Da),this.Da=null),bi(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
r.start=function(){this.enabled=!0;this.Da||(this.Da=this.i.setTimeout(this.o,this.j),this.u=Ya())};
r.stop=function(){this.enabled=!1;this.Da&&(this.i.clearTimeout(this.Da),this.Da=null)};
r.aa=function(){Ii.Aa.aa.call(this);this.stop();delete this.i};function Ji(a){F.call(this);this.H=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.B=new Set;this.flushInterval=3E4;this.h=new Ii(this.flushInterval);this.h.listen("tick",this.zb,!1,this);rc(this,this.h)}
w(Ji,F);r=Ji.prototype;r.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function Ki(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.zb()}
r.zb=function(){var a=this.i.values();a=[].concat(qa(a)).filter(function(b){return b.h.size});
a.length&&this.H.flush(a,this.u);Li(a);this.j=0;this.h.enabled&&this.h.stop()};
r.Ha=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Ch(a,b))};
r.lb=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Dh(a,b))};
function Mi(a,b){return a.B.has(b)?void 0:a.i.get(b)}
r.ib=function(a){this.Gd(a,1,B.apply(1,arguments))};
r.Gd=function(a,b){var c=B.apply(2,arguments),d=Mi(this,a);d&&d instanceof Ch&&(d.j(b,c),Ki(this))};
r.record=function(a,b){var c=B.apply(2,arguments),d=Mi(this,a);d&&d instanceof Dh&&(d.record(b,c),Ki(this))};
function Li(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Ni(){}
Ni.prototype.serialize=function(a){var b=[];Oi(this,a,b);return b.join("")};
function Oi(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Oi(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Pi(d,c),c.push(":"),Oi(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Pi(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Qi={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Ri=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Pi(a,b){b.push('"',a.replace(Ri,function(c){var d=Qi[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Qi[c]=d);return d}),'"')}
;function Si(){ai.call(this);this.headers=new Map;this.i=!1;this.K=null;this.o=this.Y="";this.j=this.U=this.B=this.R=!1;this.H=0;this.u=null;this.ja="";this.ga=!1}
Za(Si,ai);var Ti=/^https?$/i,Ui=["POST","PUT"],Vi=[];function Wi(a,b,c,d,e,f,g){var h=new Si;Vi.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Qd,!0,void 0,void 0);f&&(h.H=Math.max(0,f));g&&(h.ga=g);h.send(a,c,d,e)}
r=Si.prototype;r.Qd=function(){this.dispose();Pb(Vi,this)};
r.send=function(a,b,c,d){if(this.K)throw Error("[goog.net.XhrIo] Object is active with another request="+this.Y+"; newUri="+a);b=b?b.toUpperCase():"GET";this.Y=a;this.o="";this.R=!1;this.i=!0;this.K=new XMLHttpRequest;this.K.onreadystatechange=di(Wa(this.md,this));try{this.getStatus(),this.U=!0,this.K.open(b,String(a),!0),this.U=!1}catch(g){this.getStatus();Xi(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,d[e]);else if(typeof d.keys===
"function"&&typeof d.get==="function"){e=z(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(Jb(Ui,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=z(c);for(d=b.next();!d.done;d=b.next())c=z(d.value),d=c.next().value,c=c.next().value,this.K.setRequestHeader(d,c);this.ja&&(this.K.responseType=this.ja);"withCredentials"in this.K&&this.K.withCredentials!==this.ga&&(this.K.withCredentials=this.ga);try{this.u&&(clearTimeout(this.u),this.u=null),this.H>0&&(this.getStatus(),this.u=setTimeout(this.mf.bind(this),this.H)),
this.getStatus(),this.B=!0,this.K.send(a),this.B=!1}catch(g){this.getStatus(),Xi(this,g)}};
r.mf=function(){typeof Ka!="undefined"&&this.K&&(this.o="Timed out after "+this.H+"ms, aborting",this.getStatus(),bi(this,"timeout"),this.abort(8))};
function Xi(a,b){a.i=!1;a.K&&(a.j=!0,a.K.abort(),a.j=!1);a.o=b;Yi(a);Zi(a)}
function Yi(a){a.R||(a.R=!0,bi(a,"complete"),bi(a,"error"))}
r.abort=function(){this.K&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.K.abort(),this.j=!1,bi(this,"complete"),bi(this,"abort"),Zi(this))};
r.aa=function(){this.K&&(this.i&&(this.i=!1,this.j=!0,this.K.abort(),this.j=!1),Zi(this,!0));Si.Aa.aa.call(this)};
r.md=function(){this.da||(this.U||this.B||this.j?$i(this):this.Ce())};
r.Ce=function(){$i(this)};
function $i(a){if(a.i&&typeof Ka!="undefined")if(a.B&&(a.K?a.K.readyState:0)==4)setTimeout(a.md.bind(a),0);else if(bi(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(aj(a))bi(a,"complete"),bi(a,"success");else{try{var b=(a.K?a.K.readyState:0)>2?a.K.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Yi(a)}}finally{Zi(a)}}}
function Zi(a,b){if(a.K){a.u&&(clearTimeout(a.u),a.u=null);var c=a.K;a.K=null;b||bi(a,"ready");try{c.onreadystatechange=null}catch(d){}}}
r.isActive=function(){return!!this.K};
r.isComplete=function(){return(this.K?this.K.readyState:0)==4};
function aj(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=Zb(1,String(a.Y)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!Ti.test(a?a.toLowerCase():"");c=b}return c}
r.getStatus=function(){try{return(this.K?this.K.readyState:0)>2?this.K.status:-1}catch(a){return-1}};
r.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function bj(){}
bj.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
Wi(a.url,function(d){d=d.target;if(aj(d)){try{var e=d.K?d.K.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.qc,a.timeoutMillis,a.withCredentials)};
bj.prototype.ec=function(){return 1};function cj(a,b){this.logger=a;this.event=b;this.startTime=dj()}
cj.prototype.done=function(){this.logger.Kb(this.event,dj()-this.startTime)};
function ej(){tc.apply(this,arguments)}
w(ej,tc);function fj(a,b){var c=dj();b=b();a.Kb("n",dj()-c);return b}
function gj(){ej.apply(this,arguments)}
w(gj,ej);r=gj.prototype;r.Dc=function(){};
r.sb=function(){};
r.Kb=function(){};
r.Ea=function(){};
r.Sb=function(){};
r.yd=function(){};
function hj(a){return{le:new vc(a),oe:new xc(a),ne:new wc(a),ef:new Ac(a),ff:new Bc(a),gf:new Cc(a),Nd:new yc(a),Od:new zc(a),errorCount:new Gc(a),eventCount:new Ec(a),Yd:new Fc(a),Lh:new Dc(a),Nh:new Hc(a),jh:new Ic(a),Mh:new Jc(a)}}
function ij(a){var b=uh(th(new sh(1828,"0"),"34"),new bj);a.length&&vh(b,Wf(new Vf,a));a=new xh(1828,"","",!1,"",wh(b));rc(a,b);var c=new Ji(a);c.addOnDisposeCallback(function(){return void c.zb()});
rc(c,a);c.o=1E5;c.flushInterval=3E4;c.h.setInterval(3E4);return c}
function jj(a,b){F.call(this);var c=this;this.callback=a;this.i=b;this.h=-b;b&&this.addOnDisposeCallback(function(){return void clearTimeout(c.timer)})}
w(jj,F);function kj(a){if(a.timer===void 0){var b=dj(),c=a.h+a.i-b;c>0?a.timer=setTimeout(function(){a.timer=void 0;kj(a)},c):(a.h=b,a.callback())}}
function lj(a,b,c){ej.call(this);this.metrics=a;this.ia=b;this.gb=c;this.h=new Map;this.i=new Map;this.h.set("h",1);this.h.set("u",2);this.h.set("k",3);this.i.set(25,1);this.i.set(26,2);this.i.set(27,3);this.i.set(28,4)}
w(lj,ej);lj.prototype.Dc=function(a){this.metrics.gf.record(a,this.ia)};
lj.prototype.sb=function(a){a==="t"?this.metrics.le.h.ib("/client_streamz/bg/fic",this.ia):a==="n"?this.metrics.ef.h.ib("/client_streamz/bg/fsc",this.ia):a==="h"||a==="u"||a==="k"?(a=this.h.get(a))&&this.metrics.Nd.h.ib("/client_streamz/bg/fcc",a,this.ia):this.metrics.eventCount.h.ib("/client_streamz/bg/ec",a,this.ia)};
lj.prototype.Kb=function(a,b){a==="t"?this.metrics.oe.record(b,this.ia):a==="n"?this.metrics.ff.record(b,this.ia):a==="h"||a==="u"||a==="k"?(a=this.h.get(a))&&this.metrics.Od.record(b,a,this.ia):this.metrics.Yd.record(b,a,this.gb,this.ia)};
lj.prototype.Ea=function(a){var b=this.i.get(a);b?this.metrics.ne.h.ib("/client_streamz/bg/fiec",this.ia,b):this.metrics.errorCount.h.ib("/client_streamz/bg/cec",a,this.gb,this.ia)};
function mj(a,b){b=b===void 0?[]:b;a={ia:a.ia||"_",gb:a.gb||"",dc:a.dc||[],jc:a.jc|0};b=ij(a.dc.concat(b));lj.call(this,hj(b),a.ia,a.gb);var c=this;this.options=a;this.service=b;this.j=new jj(function(){return void c.service.zb()},a.jc);
this.addOnDisposeCallback(function(){c.j.dispose();c.service.dispose()})}
w(mj,lj);mj.prototype.yd=function(a){var b=this;this.j.dispose();this.service.dispose();this.service=ij(this.options.dc.concat(a));this.j=new jj(function(){return void b.service.zb()},this.options.jc);
this.metrics=hj(this.service)};
mj.prototype.Sb=function(){kj(this.j)};
function dj(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function mc(a){this.G=K(a)}
w(mc,L);function nj(a){this.G=K(a)}
w(nj,L);var oj=Uf(nj);function pj(a){this.G=K(a,0,"bfkj")}
w(pj,L);var qj=function(a){return Vd(function(b){return b instanceof a&&!(Hd(b.G)&2)})}(pj);function rj(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function sj(a){function b(y,G,I,O){Promise.resolve().then(function(){m.done();l.Sb();l.dispose();k.resolve({Kd:y,bf:G,Ah:I,lh:O})})}
function c(y,G,I,O){if(!d.logger.da){var T="k";G?T="h":I&&(T="u");T!=="k"?O!==0&&(d.logger.sb(T),d.logger.Kb(T,y)):d.i<=0?(d.logger.sb(T),d.logger.Kb(T,y),d.i=Math.floor(Math.random()*200)):d.i--}}
F.call(this);var d=this;this.i=Math.floor(Math.random()*200);if("challenge"in a&&qj(a.challenge)){var e=Cf(a.challenge,4);var f=Cf(a.challenge,5);Cf(a.challenge,7).length?this.h=oj(Cf(a.challenge,7)):this.h=wf(a.challenge,nj,6)}else e=a.program,f=a.he;this.addOnDisposeCallback(function(){var y,G,I;return A(function(O){if(O.h==1)return O.yield(d.j,2);y=O.i;G=y.bf;(I=G)==null||I();O.h=0})});
var g;if((g=a.kd)==null?0:g.disable)this.logger=new gj;else{var h;g=((h=this.h)==null?0:Bf(h))?kc(this.h):[];a.Rd?(this.logger=a.Rd.share(),g.length&&this.logger.yd(g)):(h=a.kd||{},this.logger=new mj({ia:h.ia,gb:h.gb,dc:h.oh,jc:h.yh},g))}rc(this,this.logger);var k=new rj;this.j=k.promise;this.logger.sb("t");var l=this.logger.share(),m=new cj(l,"t");if(!C[f])throw this.logger.Ea(25),Error("EGOU");if(!C[f].a)throw this.logger.Ea(26),Error("ELIU");try{var n=C[f].a;f=[];h=[];var p;if((p=this.h)==null?
0:Bf(p)){var t=kc(this.h);for(p=0;p<t.length;p++)f.push(t[p]),h.push(1);var v=oc(this.h);for(t=0;t<v.length;t++)f.push(v[t]),h.push(2)}var x;this.o=z(n(e,b,!0,a.Kh,c,[f,h],(x=this.h)==null?void 0:Cf(x,5))).next().value;this.af=k.promise.then(function(){})}catch(y){throw this.logger.Ea(28),y;
}}
w(sj,F);sj.prototype.snapshot=function(a){if(this.da)throw Error("Already disposed");this.logger.sb("n");var b=this.logger.share();return this.j.then(function(c){var d=c.Kd;return new Promise(function(e){var f=new cj(b,"n");d(function(g){f.done();b.Dc(g.length);b.Sb();b.dispose();e(g)},[a.Xc,
a.cf,a.sf,a.df])})})};
sj.prototype.vd=function(a){var b=this;if(this.da)throw Error("Already disposed");this.logger.sb("n");var c=fj(this.logger,function(){return b.o([a.Xc,a.cf,a.sf,a.df])});
this.logger.Dc(c.length);this.logger.Sb();return c};var tj=window;function uj(a){var b=vj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function wj(){var a=[];uj(function(b){a.push(b)});
return a}
var vj={tf:"allow-forms",uf:"allow-modals",vf:"allow-orientation-lock",wf:"allow-pointer-lock",xf:"allow-popups",yf:"allow-popups-to-escape-sandbox",zf:"allow-presentation",Af:"allow-same-origin",Bf:"allow-scripts",Cf:"allow-top-navigation",Df:"allow-top-navigation-by-user-activation"},xj=qi(function(){return wj()});
function yj(){var a=zj(),b={};Kb(xj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function zj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Aj(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Bj=(new Date).getTime();function Cj(a){ai.call(this);var b=this;this.B=this.j=0;this.Ca=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return A(function(e){return e.yield(Dj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.B||Ej(this)}
w(Cj,ai);function Fj(){var a=Gj;Cj.h||(Cj.h=new Cj(a));return Cj.h}
Cj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ca.qa(this.B);delete Cj.h};
Cj.prototype.wa=function(){return this.i};
function Ej(a){a.B=a.Ca.pa(function(){var b;return A(function(c){if(c.h==1)return a.i?((b=window.navigator)==null?0:b.onLine)?c.F(3):c.yield(Dj(a),3):c.yield(Dj(a),3);Ej(a);c.h=0})},3E4)}
function Dj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Ca.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.R=[h.j];h.o=0;h.D=0;a.u=void 0;a.j&&(a.Ca.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?bi(a,"networkstatus-online"):bi(a,"networkstatus-offline"));c(g);Aa(h);break;case 2:za(h),g=!1,h.F(3)}})})}
;function Hj(){this.data=[];this.h=-1}
Hj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Hj.prototype.get=function(a){return!!this.data[a]};
function Ij(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Jj(){this.blockSize=-1}
;function Kj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.D=[];this.u=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
Za(Kj,Jj);Kj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function Lj(a,b,c){c||(c=0);var d=a.u;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(b=16;b<80;b++)c=d[b-3]^d[b-8]^d[b-14]^d[b-16],d[b]=(c<<1|c>>>31)&4294967295;b=a.h[0];c=a.h[1];e=a.h[2];for(var f=a.h[3],g=a.h[4],h,k,l=0;l<80;l++)l<40?l<20?(h=f^c&(e^f),k=1518500249):(h=c^e^f,k=1859775393):l<60?(h=c&e|f&(c|e),k=2400959708):(h=c^e^f,k=3395469782),
h=(b<<5|b>>>27)+h+g+k+d[l]&4294967295,g=f,f=e,e=(c<<30|c>>>2)&4294967295,c=b,b=h;a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+e&4294967295;a.h[3]=a.h[3]+f&4294967295;a.h[4]=a.h[4]+g&4294967295}
Kj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.D,f=this.i;d<b;){if(f==0)for(;d<=c;)Lj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}this.i=f;this.o+=b}};
Kj.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.D[c]=b&255,b/=256;Lj(this,this.D);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Mj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Nj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Oj(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Mj(a).match(/\S+/g)||[],b=Jb(a,b)>=0);return b}
function Pj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Oj(a,"inverted-hdpi")&&Nj(a,Array.prototype.filter.call(a.classList?a.classList:Mj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function Qj(){}
Qj.prototype.next=function(){return Rj};
var Rj={done:!0,value:void 0};Qj.prototype.kb=function(){return this};function Sj(a){if(a instanceof Tj||a instanceof Uj||a instanceof Vj)return a;if(typeof a.next=="function")return new Tj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new Tj(function(){return a[Symbol.iterator]()});
if(typeof a.kb=="function")return new Tj(function(){return a.kb()});
throw Error("Not an iterator or iterable.");}
function Tj(a){this.h=a}
Tj.prototype.kb=function(){return new Uj(this.h())};
Tj.prototype[Symbol.iterator]=function(){return new Vj(this.h())};
Tj.prototype.i=function(){return new Vj(this.h())};
function Uj(a){this.h=a}
w(Uj,Qj);Uj.prototype.next=function(){return this.h.next()};
Uj.prototype[Symbol.iterator]=function(){return new Vj(this.h)};
Uj.prototype.i=function(){return new Vj(this.h)};
function Vj(a){Tj.call(this,function(){return a});
this.j=a}
w(Vj,Tj);Vj.prototype.next=function(){return this.j.next()};function M(a){F.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.B=!!a}
Za(M,F);r=M.prototype;r.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
r.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Rb(a)}return!1};
r.Rb=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Pb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
r.jb=function(a,b){var c=this.i[a];if(c){var d=Array(arguments.length-1),e=arguments.length,f;for(f=1;f<e;f++)d[f-1]=arguments[f];if(this.B)for(f=0;f<c.length;f++)e=c[f],Wj(this.h[e+1],this.h[e+2],d);else{this.o++;try{for(f=0,e=c.length;f<e&&!this.da;f++){var g=c[f];this.h[g+1].apply(this.h[g+2],d)}}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.Rb(c)}}return f!=0}return!1};
function Wj(a,b,c){mi(function(){a.apply(b,c)})}
r.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Rb,this),delete this.i[a])}else this.h.length=0,this.i={}};
r.aa=function(){M.Aa.aa.call(this);this.clear();this.j.length=0};function Xj(a){this.h=a}
Xj.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Ni).serialize(b))};
Xj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Xj.prototype.remove=function(a){this.h.remove(a)};function Yj(a){this.h=a}
Za(Yj,Xj);function Zj(a){this.data=a}
function ak(a){return a===void 0||a instanceof Zj?a:new Zj(a)}
Yj.prototype.set=function(a,b){Yj.Aa.set.call(this,a,ak(b))};
Yj.prototype.i=function(a){a=Yj.Aa.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Yj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function bk(a){this.h=a}
Za(bk,Yj);bk.prototype.set=function(a,b,c){if(b=ak(b)){if(c){if(c<Ya()){bk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Ya()}bk.Aa.set.call(this,a,b)};
bk.prototype.i=function(a){var b=bk.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Ya()||c&&c>Ya())bk.prototype.remove.call(this,a);else return b}};function ck(){}
;function dk(){}
Za(dk,ck);dk.prototype[Symbol.iterator]=function(){return Sj(this.kb(!0)).i()};
dk.prototype.clear=function(){var a=Array.from(this);a=z(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ek(a){this.h=a;this.i=null}
Za(ek,dk);r=ek.prototype;r.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
r.set=function(a,b){fk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
r.get=function(a){fk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
r.remove=function(a){fk(this);this.h.removeItem(a)};
r.kb=function(a){fk(this);var b=0,c=this.h,d=new Qj;d.next=function(){if(b>=c.length)return Rj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
r.clear=function(){fk(this);this.h.clear()};
r.key=function(a){fk(this);return this.h.key(a)};
function fk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Kc(Error("Storage mechanism: Storage unavailable"))}
;function gk(){var a=null;try{a=C.localStorage||null}catch(b){}ek.call(this,a)}
Za(gk,ek);function hk(a,b){this.i=a;this.h=b+"::"}
Za(hk,dk);hk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
hk.prototype.get=function(a){return this.i.get(this.h+a)};
hk.prototype.remove=function(a){this.i.remove(this.h+a)};
hk.prototype.kb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Qj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var N={},ik=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";N.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
N.Oc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var jk={mb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
bd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},kk={mb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
bd:function(a){return[].concat.apply([],a)}};
N.Ze=function(){ik?(N.hb=Uint8Array,N.Ga=Uint16Array,N.Fd=Int32Array,N.assign(N,jk)):(N.hb=Array,N.Ga=Array,N.Fd=Array,N.assign(N,kk))};
N.Ze();var lk=!0;try{new Uint8Array(1)}catch(a){lk=!1}
function mk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new N.hb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var nk={};nk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var ok={},pk,qk=[],rk=0;rk<256;rk++){pk=rk;for(var sk=0;sk<8;sk++)pk=pk&1?3988292384^pk>>>1:pk>>>1;qk[rk]=pk}ok=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^qk[(a^b[d])&255];return a^-1};var tk={};tk={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function uk(a){for(var b=a.length;--b>=0;)a[b]=0}
var vk=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],wk=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],xk=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],yk=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],zk=Array(576);uk(zk);var Ak=Array(60);uk(Ak);var Bk=Array(512);uk(Bk);var Ck=Array(256);uk(Ck);var Dk=Array(29);uk(Dk);var Ek=Array(30);uk(Ek);function Fk(a,b,c,d,e){this.wd=a;this.ce=b;this.be=c;this.Vd=d;this.Ae=e;this.ed=a&&a.length}
var Gk,Hk,Ik;function Jk(a,b){this.Zc=a;this.ub=0;this.Ta=b}
function Kk(a,b){a.X[a.pending++]=b&255;a.X[a.pending++]=b>>>8&255}
function Lk(a,b,c){a.ha>16-c?(a.oa|=b<<a.ha&65535,Kk(a,a.oa),a.oa=b>>16-a.ha,a.ha+=c-16):(a.oa|=b<<a.ha&65535,a.ha+=c)}
function Mk(a,b,c){Lk(a,c[b*2],c[b*2+1])}
function Nk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Ok(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Nk(d[e]++,e))}
function Pk(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.Xa[b*2]=0;for(b=0;b<19;b++)a.ka[b*2]=0;a.ra[512]=1;a.Na=a.yb=0;a.ya=a.matches=0}
function Qk(a){a.ha>8?Kk(a,a.oa):a.ha>0&&(a.X[a.pending++]=a.oa);a.oa=0;a.ha=0}
function Rk(a,b,c){Qk(a);Kk(a,c);Kk(a,~c);N.mb(a.X,a.window,b,c,a.pending);a.pending+=c}
function Sk(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Tk(a,b,c){for(var d=a.ba[c],e=c<<1;e<=a.La;){e<a.La&&Sk(b,a.ba[e+1],a.ba[e],a.depth)&&e++;if(Sk(b,d,a.ba[e],a.depth))break;a.ba[c]=a.ba[e];c=e;e<<=1}a.ba[c]=d}
function Uk(a,b,c){var d=0;if(a.ya!==0){do{var e=a.X[a.Eb+d*2]<<8|a.X[a.Eb+d*2+1];var f=a.X[a.Cc+d];d++;if(e===0)Mk(a,f,b);else{var g=Ck[f];Mk(a,g+256+1,b);var h=vk[g];h!==0&&(f-=Dk[g],Lk(a,f,h));e--;g=e<256?Bk[e]:Bk[256+(e>>>7)];Mk(a,g,c);h=wk[g];h!==0&&(e-=Ek[g],Lk(a,e,h))}}while(d<a.ya)}Mk(a,256,b)}
function Vk(a,b){var c=b.Zc,d=b.Ta.wd,e=b.Ta.ed,f=b.Ta.Vd,g,h=-1;a.La=0;a.pb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.ba[++a.La]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.La<2;){var k=a.ba[++a.La]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Na--;e&&(a.yb-=d[k*2+1])}b.ub=h;for(g=a.La>>1;g>=1;g--)Tk(a,c,g);k=f;do g=a.ba[1],a.ba[1]=a.ba[a.La--],Tk(a,c,1),d=a.ba[1],a.ba[--a.pb]=g,a.ba[--a.pb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.ba[1]=k++,Tk(a,c,1);while(a.La>=
2);a.ba[--a.pb]=a.ba[1];g=b.Zc;k=b.ub;d=b.Ta.wd;e=b.Ta.ed;f=b.Ta.ce;var l=b.Ta.be,m=b.Ta.Ae,n,p=0;for(n=0;n<=15;n++)a.Ia[n]=0;g[a.ba[a.pb]*2+1]=0;for(b=a.pb+1;b<573;b++){var t=a.ba[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,p++);g[t*2+1]=n;if(!(t>k)){a.Ia[n]++;var v=0;t>=l&&(v=f[t-l]);var x=g[t*2];a.Na+=x*(n+v);e&&(a.yb+=x*(d[t*2+1]+v))}}if(p!==0){do{for(n=m-1;a.Ia[n]===0;)n--;a.Ia[n]--;a.Ia[n+1]+=2;a.Ia[m]--;p-=2}while(p>0);for(n=m;n!==0;n--)for(t=a.Ia[n];t!==0;)d=a.ba[--b],d>k||(g[d*2+1]!==n&&(a.Na+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}Ok(c,h,a.Ia)}
function Wk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ka[l*2]+=g:l!==0?(l!==e&&a.ka[l*2]++,a.ka[32]++):g<=10?a.ka[34]++:a.ka[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Xk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Mk(a,l,a.ka);while(--g!==0)}else l!==0?(l!==e&&(Mk(a,l,a.ka),g--),Mk(a,16,a.ka),Lk(a,g-3,2)):g<=10?(Mk(a,17,a.ka),Lk(a,g-3,3)):(Mk(a,18,a.ka),Lk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Yk(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var Zk=!1;function $k(a,b,c){a.X[a.Eb+a.ya*2]=b>>>8&255;a.X[a.Eb+a.ya*2+1]=b&255;a.X[a.Cc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Ck[c]+256+1)*2]++,a.Xa[(b<256?Bk[b]:Bk[256+(b>>>7)])*2]++);return a.ya===a.Jb-1}
;function al(a,b){a.msg=tk[b];return b}
function bl(a){for(var b=a.length;--b>=0;)a[b]=0}
function cl(a){var b=a.state,c=b.pending;c>a.S&&(c=a.S);c!==0&&(N.mb(a.output,b.X,b.Mb,c,a.vb),a.vb+=c,b.Mb+=c,a.Pc+=c,a.S-=c,b.pending-=c,b.pending===0&&(b.Mb=0))}
function dl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.M.xc===2&&(a.M.xc=Yk(a));Vk(a,a.ic);Vk(a,a.ac);Wk(a,a.ra,a.ic.ub);Wk(a,a.Xa,a.ac.ub);Vk(a,a.Uc);for(e=18;e>=3&&a.ka[yk[e]*2+1]===0;e--);a.Na+=3*(e+1)+5+5+4;var f=a.Na+3+7>>>3;var g=a.yb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Lk(a,b?1:0,3),Rk(a,c,d);else if(a.strategy===4||g===f)Lk(a,2+(b?1:0),3),Uk(a,zk,Ak);else{Lk(a,4+(b?1:0),3);c=a.ic.ub+1;d=a.ac.ub+1;e+=1;Lk(a,c-257,5);Lk(a,d-1,5);Lk(a,e-4,4);for(f=0;f<e;f++)Lk(a,
a.ka[yk[f]*2+1],3);Xk(a,a.ra,c-1);Xk(a,a.Xa,d-1);Uk(a,a.ra,a.Xa)}Pk(a);b&&Qk(a);a.va=a.v;cl(a.M)}
function P(a,b){a.X[a.pending++]=b}
function el(a,b){a.X[a.pending++]=b>>>8&255;a.X[a.pending++]=b&255}
function fl(a,b){var c=a.jd,d=a.v,e=a.xa,f=a.ld,g=a.v>a.ma-262?a.v-(a.ma-262):0,h=a.window,k=a.Ua,l=a.Fa,m=a.v+258,n=h[d+e-1],p=h[d+e];a.xa>=a.dd&&(c>>=2);f>a.A&&(f=a.A);do{var t=b;if(h[t+e]===p&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.tb=b;e=t;if(t>=f)break;n=h[d+e-1];p=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.A?e:a.A}
function gl(a){var b=a.ma,c;do{var d=a.Dd-a.A-a.v;if(a.v>=b+(b-262)){N.mb(a.window,a.window,b,b,0);a.tb-=b;a.v-=b;a.va-=b;var e=c=a.hc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Fa[--e],a.Fa[e]=f>=b?f-b:0;while(--c);d+=b}if(a.M.na===0)break;e=a.M;c=a.window;f=a.v+a.A;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,N.mb(c,e.input,e.cb,g,f),e.state.wrap===1?e.J=nk(e.J,c,g,f):e.state.wrap===2&&(e.J=ok(e.J,c,g,f)),e.cb+=g,e.fb+=g,c=g);a.A+=c;if(a.A+a.sa>=3)for(d=a.v-a.sa,a.P=a.window[d],
a.P=(a.P<<a.Ka^a.window[d+1])&a.Ja;a.sa&&!(a.P=(a.P<<a.Ka^a.window[d+3-1])&a.Ja,a.Fa[d&a.Ua]=a.head[a.P],a.head[a.P]=d,d++,a.sa--,a.A+a.sa<3););}while(a.A<262&&a.M.na!==0)}
function hl(a,b){for(var c;;){if(a.A<262){gl(a);if(a.A<262&&b===0)return 1;if(a.A===0)break}c=0;a.A>=3&&(a.P=(a.P<<a.Ka^a.window[a.v+3-1])&a.Ja,c=a.Fa[a.v&a.Ua]=a.head[a.P],a.head[a.P]=a.v);c!==0&&a.v-c<=a.ma-262&&(a.T=fl(a,c));if(a.T>=3)if(c=$k(a,a.v-a.tb,a.T-3),a.A-=a.T,a.T<=a.Ec&&a.A>=3){a.T--;do a.v++,a.P=(a.P<<a.Ka^a.window[a.v+3-1])&a.Ja,a.Fa[a.v&a.Ua]=a.head[a.P],a.head[a.P]=a.v;while(--a.T!==0);a.v++}else a.v+=a.T,a.T=0,a.P=a.window[a.v],a.P=(a.P<<a.Ka^a.window[a.v+1])&a.Ja;else c=$k(a,0,
a.window[a.v]),a.A--,a.v++;if(c&&(dl(a,!1),a.M.S===0))return 1}a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.M.S===0?3:4):a.ya&&(dl(a,!1),a.M.S===0)?1:2}
function il(a,b){for(var c,d;;){if(a.A<262){gl(a);if(a.A<262&&b===0)return 1;if(a.A===0)break}c=0;a.A>=3&&(a.P=(a.P<<a.Ka^a.window[a.v+3-1])&a.Ja,c=a.Fa[a.v&a.Ua]=a.head[a.P],a.head[a.P]=a.v);a.xa=a.T;a.od=a.tb;a.T=2;c!==0&&a.xa<a.Ec&&a.v-c<=a.ma-262&&(a.T=fl(a,c),a.T<=5&&(a.strategy===1||a.T===3&&a.v-a.tb>4096)&&(a.T=2));if(a.xa>=3&&a.T<=a.xa){d=a.v+a.A-3;c=$k(a,a.v-1-a.od,a.xa-3);a.A-=a.xa-1;a.xa-=2;do++a.v<=d&&(a.P=(a.P<<a.Ka^a.window[a.v+3-1])&a.Ja,a.Fa[a.v&a.Ua]=a.head[a.P],a.head[a.P]=a.v);
while(--a.xa!==0);a.ab=0;a.T=2;a.v++;if(c&&(dl(a,!1),a.M.S===0))return 1}else if(a.ab){if((c=$k(a,0,a.window[a.v-1]))&&dl(a,!1),a.v++,a.A--,a.M.S===0)return 1}else a.ab=1,a.v++,a.A--}a.ab&&($k(a,0,a.window[a.v-1]),a.ab=0);a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.M.S===0?3:4):a.ya&&(dl(a,!1),a.M.S===0)?1:2}
function jl(a,b){for(var c,d,e,f=a.window;;){if(a.A<=258){gl(a);if(a.A<=258&&b===0)return 1;if(a.A===0)break}a.T=0;if(a.A>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.T=258-(e-d);a.T>a.A&&(a.T=a.A)}a.T>=3?(c=$k(a,1,a.T-3),a.A-=a.T,a.v+=a.T,a.T=0):(c=$k(a,0,a.window[a.v]),a.A--,a.v++);if(c&&(dl(a,!1),a.M.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.M.S===0?3:4):
a.ya&&(dl(a,!1),a.M.S===0)?1:2}
function kl(a,b){for(var c;;){if(a.A===0&&(gl(a),a.A===0)){if(b===0)return 1;break}a.T=0;c=$k(a,0,a.window[a.v]);a.A--;a.v++;if(c&&(dl(a,!1),a.M.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.M.S===0?3:4):a.ya&&(dl(a,!1),a.M.S===0)?1:2}
function ll(a,b,c,d,e){this.je=a;this.ze=b;this.Be=c;this.ye=d;this.de=e}
var ml;ml=[new ll(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.A<=1){gl(a);if(a.A===0&&b===0)return 1;if(a.A===0)break}a.v+=a.A;a.A=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.A=a.v-d,a.v=d,dl(a,!1),a.M.S===0)return 1;if(a.v-a.va>=a.ma-262&&(dl(a,!1),a.M.S===0))return 1}a.sa=0;if(b===4)return dl(a,!0),a.M.S===0?3:4;a.v>a.va&&dl(a,!1);return 1}),
new ll(4,4,8,4,hl),new ll(4,5,16,8,hl),new ll(4,6,32,32,hl),new ll(4,4,16,16,il),new ll(8,16,32,32,il),new ll(8,16,128,128,il),new ll(8,32,128,256,il),new ll(32,128,258,1024,il),new ll(32,258,258,4096,il)];
function nl(){this.M=null;this.status=0;this.X=null;this.wrap=this.pending=this.Mb=this.za=0;this.I=null;this.Ba=0;this.method=8;this.rb=-1;this.Ua=this.Rc=this.ma=0;this.window=null;this.Dd=0;this.head=this.Fa=null;this.ld=this.dd=this.strategy=this.level=this.Ec=this.jd=this.xa=this.A=this.tb=this.v=this.ab=this.od=this.T=this.va=this.Ka=this.Ja=this.Ac=this.hc=this.P=0;this.ra=new N.Ga(1146);this.Xa=new N.Ga(122);this.ka=new N.Ga(78);bl(this.ra);bl(this.Xa);bl(this.ka);this.Uc=this.ac=this.ic=
null;this.Ia=new N.Ga(16);this.ba=new N.Ga(573);bl(this.ba);this.pb=this.La=0;this.depth=new N.Ga(573);bl(this.depth);this.ha=this.oa=this.sa=this.matches=this.yb=this.Na=this.Eb=this.ya=this.Jb=this.Cc=0}
function ol(a,b){if(!a||!a.state||b>5||b<0)return a?al(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return al(a,a.S===0?-5:-2);c.M=a;var d=c.rb;c.rb=b;if(c.status===42)if(c.wrap===2)a.J=0,P(c,31),P(c,139),P(c,8),c.I?(P(c,(c.I.text?1:0)+(c.I.Pa?2:0)+(c.I.extra?4:0)+(c.I.name?8:0)+(c.I.comment?16:0)),P(c,c.I.time&255),P(c,c.I.time>>8&255),P(c,c.I.time>>16&255),P(c,c.I.time>>24&255),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,c.I.os&255),c.I.extra&&c.I.extra.length&&
(P(c,c.I.extra.length&255),P(c,c.I.extra.length>>8&255)),c.I.Pa&&(a.J=ok(a.J,c.X,c.pending,0)),c.Ba=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,3),c.status=113);else{var e=8+(c.Rc-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;el(c,e+(31-e%31));c.v!==0&&(el(c,a.J>>>16),el(c,a.J&65535));a.J=1}if(c.status===69)if(c.I.extra){for(e=c.pending;c.Ba<(c.I.extra.length&65535)&&(c.pending!==c.za||
(c.I.Pa&&c.pending>e&&(a.J=ok(a.J,c.X,c.pending-e,e)),cl(a),e=c.pending,c.pending!==c.za));)P(c,c.I.extra[c.Ba]&255),c.Ba++;c.I.Pa&&c.pending>e&&(a.J=ok(a.J,c.X,c.pending-e,e));c.Ba===c.I.extra.length&&(c.Ba=0,c.status=73)}else c.status=73;if(c.status===73)if(c.I.name){e=c.pending;do{if(c.pending===c.za&&(c.I.Pa&&c.pending>e&&(a.J=ok(a.J,c.X,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ba<c.I.name.length?c.I.name.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.I.Pa&&c.pending>
e&&(a.J=ok(a.J,c.X,c.pending-e,e));f===0&&(c.Ba=0,c.status=91)}else c.status=91;if(c.status===91)if(c.I.comment){e=c.pending;do{if(c.pending===c.za&&(c.I.Pa&&c.pending>e&&(a.J=ok(a.J,c.X,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ba<c.I.comment.length?c.I.comment.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.I.Pa&&c.pending>e&&(a.J=ok(a.J,c.X,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.I.Pa?(c.pending+2>c.za&&cl(a),c.pending+2<=c.za&&(P(c,a.J&
255),P(c,a.J>>8&255),a.J=0,c.status=113)):c.status=113);if(c.pending!==0){if(cl(a),a.S===0)return c.rb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return al(a,-5);if(c.status===666&&a.na!==0)return al(a,-5);if(a.na!==0||c.A!==0||b!==0&&c.status!==666){d=c.strategy===2?kl(c,b):c.strategy===3?jl(c,b):ml[c.level].de(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.S===0&&(c.rb=-1),0;if(d===2&&(b===1?(Lk(c,2,3),Mk(c,256,zk),c.ha===16?(Kk(c,c.oa),c.oa=0,c.ha=0):c.ha>=8&&
(c.X[c.pending++]=c.oa&255,c.oa>>=8,c.ha-=8)):b!==5&&(Lk(c,0,3),Rk(c,0,0),b===3&&(bl(c.head),c.A===0&&(c.v=0,c.va=0,c.sa=0))),cl(a),a.S===0))return c.rb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(P(c,a.J&255),P(c,a.J>>8&255),P(c,a.J>>16&255),P(c,a.J>>24&255),P(c,a.fb&255),P(c,a.fb>>8&255),P(c,a.fb>>16&255),P(c,a.fb>>24&255)):(el(c,a.J>>>16),el(c,a.J&65535));cl(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var pl={};pl=function(){this.input=null;this.fb=this.na=this.cb=0;this.output=null;this.Pc=this.S=this.vb=0;this.msg="";this.state=null;this.xc=2;this.J=0};var ql=Object.prototype.toString;
function rl(a){if(!(this instanceof rl))return new rl(a);a=this.options=N.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.M=new pl;this.M.S=0;var b=this.M;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=al(b,-2);else{e===8&&(e=9);var k=new nl;b.state=k;k.M=b;k.wrap=h;k.I=null;k.Rc=e;k.ma=1<<k.Rc;k.Ua=k.ma-1;k.Ac=f+7;k.hc=1<<k.Ac;k.Ja=k.hc-1;k.Ka=~~((k.Ac+3-1)/3);k.window=new N.hb(k.ma*2);k.head=new N.Ga(k.hc);k.Fa=new N.Ga(k.ma);k.Jb=1<<f+6;k.za=k.Jb*4;k.X=new N.hb(k.za);k.Eb=1*k.Jb;k.Cc=3*k.Jb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.fb=b.Pc=0;b.xc=2;c=b.state;c.pending=0;c.Mb=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.J=c.wrap===2?
0:1;c.rb=0;if(!Zk){d=Array(16);for(f=g=0;f<28;f++)for(Dk[f]=g,e=0;e<1<<vk[f];e++)Ck[g++]=f;Ck[g-1]=f;for(f=g=0;f<16;f++)for(Ek[f]=g,e=0;e<1<<wk[f];e++)Bk[g++]=f;for(g>>=7;f<30;f++)for(Ek[f]=g<<7,e=0;e<1<<wk[f]-7;e++)Bk[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)zk[e*2+1]=8,e++,d[8]++;for(;e<=255;)zk[e*2+1]=9,e++,d[9]++;for(;e<=279;)zk[e*2+1]=7,e++,d[7]++;for(;e<=287;)zk[e*2+1]=8,e++,d[8]++;Ok(zk,287,d);for(e=0;e<30;e++)Ak[e*2+1]=5,Ak[e*2]=Nk(e,5);Gk=new Fk(zk,vk,257,286,15);Hk=new Fk(Ak,
wk,0,30,15);Ik=new Fk([],xk,0,19,7);Zk=!0}c.ic=new Jk(c.ra,Gk);c.ac=new Jk(c.Xa,Hk);c.Uc=new Jk(c.ka,Ik);c.oa=0;c.ha=0;Pk(c);c=0}else c=al(b,-2);c===0&&(b=b.state,b.Dd=2*b.ma,bl(b.head),b.Ec=ml[b.level].ze,b.dd=ml[b.level].je,b.ld=ml[b.level].Be,b.jd=ml[b.level].ye,b.v=0,b.va=0,b.A=0,b.sa=0,b.T=b.xa=2,b.ab=0,b.P=0);b=c}}else b=-2;if(b!==0)throw Error(tk[b]);a.header&&(b=this.M)&&b.state&&b.state.wrap===2&&(b.state.I=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=mk(a.dictionary):
ql.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.M;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.A)b=-2;else{b===1&&(a.J=nk(a.J,f,g,0));l.wrap=0;g>=l.ma&&(b===0&&(bl(l.head),l.v=0,l.va=0,l.sa=0),c=new N.hb(l.ma),N.mb(c,f,g-l.ma,l.ma,0),f=c,g=l.ma);c=a.na;d=a.cb;e=a.input;a.na=g;a.cb=0;a.input=f;for(gl(l);l.A>=3;){f=l.v;g=l.A-2;do l.P=(l.P<<l.Ka^l.window[f+3-1])&l.Ja,l.Fa[f&l.Ua]=l.head[l.P],l.head[l.P]=f,f++;while(--g);
l.v=f;l.A=2;gl(l)}l.v+=l.A;l.va=l.v;l.sa=l.A;l.A=0;l.T=l.xa=2;l.ab=0;a.cb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(tk[b]);this.gh=!0}}
rl.prototype.push=function(a,b){var c=this.M,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=mk(a):ql.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.cb=0;c.na=c.input.length;do{c.S===0&&(c.output=new N.hb(d),c.vb=0,c.S=d);a=ol(c,e);if(a!==1&&a!==0)return sl(this,a),this.ended=!0,!1;if(c.S===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=N.Oc(c.output,c.vb);b=f;f=f.length;if(f<65537&&(b.subarray&&lk||!b.subarray))b=
String.fromCharCode.apply(null,N.Oc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=N.Oc(c.output,c.vb),this.chunks.push(b)}while((c.na>0||c.S===0)&&a!==1);if(e===4)return(c=this.M)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=al(c,-2):(c.state=null,a=d===113?al(c,-3):0)):a=-2,sl(this,a),this.ended=!0,a===0;e===2&&(sl(this,0),c.S=0);return!0};
function sl(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):N.bd(a.chunks));a.chunks=[];a.err=b;a.msg=a.M.msg}
function tl(a,b){b=b||{};b.gzip=!0;b=new rl(b);b.push(a,!0);if(b.err)throw b.msg||tk[b.err];return b.result}
;function ul(a){if(!a)return null;a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue;var b;a?b=ib(a):b=null;return b}
;function vl(a){return ib(a===null?"null":a===void 0?"undefined":a)}
;function wl(a){this.name=a}
;var xl=new wl("rawColdConfigGroup");var yl=new wl("rawHotConfigGroup");function zl(a){this.G=K(a)}
w(zl,L);function Al(a){this.G=K(a)}
w(Al,L);Al.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new td(a,sd):vd||(vd=new td(null,sd));else if(a.constructor!==td)if(rd(a))a=a.length?new td(new Uint8Array(a),sd):vd||(vd=new td(null,sd));else throw Error();return kf(this,1,a)};var Bl=new wl("continuationCommand");var Cl=new wl("webCommandMetadata");var Dl=new wl("signalServiceEndpoint");var El={Jf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Gf:"EMBEDDED_PLAYER_MODE_DEFAULT",If:"EMBEDDED_PLAYER_MODE_PFP",Hf:"EMBEDDED_PLAYER_MODE_PFL"};var Fl=new wl("feedbackEndpoint");var $d={Kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",Uf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",Lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Bg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
Ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",Mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",Rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",Qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",Pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",Sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",Tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
Og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Nf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Mf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Of:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Pf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",Hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
Ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",Tf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",Rf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",Sf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Qf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED",
zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROUND_TRIP_HANDLING_ON_REMOTE_CONNECTION",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_BEFORE_APP_RELOAD",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_AFTER_APP_RELOAD",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_INELIGIBLE",Gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TVHTML5_MID_ROLL_THRESHOLD_REACHED",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_PENDING",
ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_ACTIVATED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_M2_ELIGIBLE",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_LANDSCAPE",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_PORTRAIT",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMBEDS_FACEOFF_UI_EVENT",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_RECEIVED"};var Gl=new wl("shareEndpoint"),Hl=new wl("shareEntityEndpoint"),Il=new wl("shareEntityServiceEndpoint"),Jl=new wl("webPlayerShareEntityServiceEndpoint");var Kl=new wl("playlistEditEndpoint");var Ll=new wl("modifyChannelNotificationPreferenceEndpoint");var Ml=new wl("unsubscribeEndpoint");var Nl=new wl("subscribeEndpoint");function Ol(){var a=Pl;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function Ql(a){D("yt.ads.biscotti.lastId_",a)}
;function Rl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Sl=C.window,Tl,Ul,Vl=(Sl==null?void 0:(Tl=Sl.yt)==null?void 0:Tl.config_)||(Sl==null?void 0:(Ul=Sl.ytcfg)==null?void 0:Ul.data_)||{};D("yt.config_",Vl);function Wl(){Rl(Vl,arguments)}
function R(a,b){return a in Vl?Vl[a]:b}
function Xl(a){var b=Vl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Yl=[];function Zl(a){Yl.forEach(function(b){return b(a)})}
function $l(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){am(b)}}:a}
function am(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Wl("ERRORS",b));Zl(a)}
function bm(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Wl("ERRORS",f))}
;var cm=/^[\w.]*$/,dm={q:!0,search_query:!0};function em(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=fm(f[0]||""),h=fm(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Qb(k,h):c[g]=[k,h]}else c[g]=h}catch(p){var l=p,m=f[0],n=String(em);l.args=[{key:m,value:f[1],query:a,method:gm===n?"unchanged":n}];dm.hasOwnProperty(m)||bm(l)}}return c}
var gm=String(em);function hm(a){var b=[];wg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Kb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function im(a){a.charAt(0)==="?"&&(a=a.substring(1));return em(a,"&")}
function jm(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),im(a.length>1?a[1]:a[0])):{}}
function km(a,b){return lm(a,b||{},!0)}
function lm(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=im(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return ec(a,e)+d}
function mm(a){if(!b)var b=window.location.href;var c=Zb(1,a),d=$b(a);c&&d?(a=a.match(Xb),b=b.match(Xb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?$b(b)===d&&(Number(Zb(4,b))||null)===(Number(Zb(4,a))||null):!0;return a}
function fm(a){return a&&a.match(cm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function nm(a){var b=om;a=a===void 0?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Bj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ma){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?tj:g;try{var h=g.history.length}catch(Ma){h=0}e.u_his=h;var k;e.u_h=(k=tj.screen)==null?void 0:k.height;var l;e.u_w=(l=tj.screen)==null?void 0:l.width;var m;e.u_ah=(m=tj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=tj.screen)==null?void 0:n.availWidth;var p;e.u_cd=(p=tj.screen)==null?void 0:p.colorDepth}catch(Ma){}h=b.h;try{var t=h.screenX;var v=h.screenY}catch(Ma){}try{var x=h.outerWidth;var y=h.outerHeight}catch(Ma){}try{var G=h.innerWidth;var I=h.innerHeight}catch(Ma){}try{var O=h.screenLeft;var T=h.screenTop}catch(Ma){}try{G=h.innerWidth,I=h.innerHeight}catch(Ma){}try{var Ja=h.screen.availWidth;var cb=h.screen.availTop}catch(Ma){}t=[O,T,t,v,Ja,cb,x,y,G,I];try{var ca=(b.h.top||window).document,Z=ca.compatMode==
"CSS1Compat"?ca.documentElement:ca.body;var na=(new vg(Z.clientWidth,Z.clientHeight)).round()}catch(Ma){na=new vg(-12245933,-12245933)}ca=na;na={};var Na=Na===void 0?C:Na;Z=new Hj;"SVGElement"in Na&&"createElementNS"in Na.document&&Z.set(0);v=yj();v["allow-top-navigation-by-user-activation"]&&Z.set(1);v["allow-popups-to-escape-sandbox"]&&Z.set(2);Na.crypto&&Na.crypto.subtle&&Z.set(3);"TextDecoder"in Na&&"TextEncoder"in Na&&Z.set(4);Na=Ij(Z);na.bc=Na;na.bih=ca.height;na.biw=ca.width;na.brdim=t.join();
b=b.i;b=(na.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,na.wgl=!!tj.WebGLRenderingContext,na);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var om=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return hm(nm(a))});Ya();navigator.userAgent.indexOf(" (CrKey ");var pm="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function qm(){if(!pm)return null;var a=pm();return"open"in a?a:null}
function rm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function sm(a,b){typeof a==="function"&&(a=$l(a));return window.setTimeout(a,b)}
;var tm="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(qa(tm),["client_dev_set_cookie"]);function S(a){a=um(a);return typeof a==="string"&&a==="false"?!1:!!a}
function wm(a,b){a=um(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function um(a){return R("EXPERIMENT_FLAGS",{})[a]}
function xm(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=z(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});d=z(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var ym={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},zm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(qa(tm)),Am=!1;function Bm(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&$l(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=qm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=Cm(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Dm(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){bm(n)}}l.send(d);return l}
function Dm(a,b){b=b===void 0?{}:b;var c=mm(a),d=R("INNERTUBE_CLIENT_NAME"),e=S("web_ajax_ignore_global_headers_if_set"),f;for(f in ym){var g=R(ym[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=R("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||($b(a)?!1:!0))){k=a;var l;if(l=S("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=$b(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=Yb(Zb(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!$b(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!$b(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&$b(a)||(b["X-YouTube-Ad-Signals"]=hm(nm()));return b}
function Em(a,b){b.method="POST";b.postParams||(b.postParams={});return Fm(a,b)}
function Fm(a,b){var c=b.format||"JSON";a=Gm(a,b);var d=Hm(a,b),e=!1,f=Im(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=rm(k),m=null,n=400<=k.status&&k.status<500,p=500<=k.status&&k.status<600;if(l||n||p)m=Jm(a,c,k,b.convertToSafeHtml);l&&(l=Km(c,k,m));m=m||{};n=b.context||C;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=sm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function Gm(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=km(a,b);return a}
function Hm(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||$b(a)&&!b.withCredentials&&$b(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=im(e),Gg(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):dc(e));f=e||f&&!zg(f);!Am&&f&&b.method!=="POST"&&(Am=!0,am(Error("AJAX request with postData should use POST")));return e}
function Jm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,bm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Lm(a):null)e={},Kb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Mm(g)})}d&&Nm(e);
return e}
function Nm(a){if(Qa(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];var e=gb();d=new zb(e?e.createHTML(d):d);a[c]=d}else Nm(a[b])}}
function Km(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Lm(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Mm(a){var b="";Kb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Cm(a){var b=window.location.search,c=$b(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&mm(a)&&(c=document.location.hostname);var d=Yb(Zb(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=im(b),f={};Kb(zm,function(g){e[g]&&(f[g]=e[g])});
return lm(a,f||{},!1)}
var Im=Bm;var Om=[{Fc:function(a){return"Cannot read property '"+a.key+"'"},
kc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Fc:function(a){return"Cannot call '"+a.key+"'"},
kc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Fc:function(a){return a.key+" is not defined"},
kc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Qm={Sa:[],Oa:[{callback:Pm,weight:500}]};function Pm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Rm(){this.Oa=[];this.Sa=[]}
var Sm;function Tm(){if(!Sm){var a=Sm=new Rm;a.Sa.length=0;a.Oa.length=0;Qm.Sa&&a.Sa.push.apply(a.Sa,Qm.Sa);Qm.Oa&&a.Oa.push.apply(a.Oa,Qm.Oa)}return Sm}
;var Um=new M;function Vm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Wm(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=Wm(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=Wm(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function Wm(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function Xm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Ym(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Vm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?Ym(f+".ve",g,h,k):0;d+=f;d+=Ym(e,a[e],b,c);if(d>500)break}}else c[b]=Zm(a),d+=c[b].length;else c[b]=Zm(a),d+=c[b].length;return d}
function Ym(a,b,c,d){c+="."+a;a=Zm(b);d[c]=a;return c.length+a.length}
function Zm(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function $m(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function an(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function bn(){this.hf=!0}
function cn(){bn.h||(bn.h=new bn);return bn.h}
function dn(a,b){a={};var c=[];"USER_SESSION_ID"in Vl&&c.push({key:"u",value:R("USER_SESSION_ID")});if(c=og(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Vl||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in Vl&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID"));return a}
;var en={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function fn(a,b,c,d,e){kg.set(""+a,b,{Lb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function gn(a){return kg.get(""+a,void 0)}
function hn(a,b,c){kg.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function jn(){if(S("embeds_web_enable_cookie_detection_fix")){if(!C.navigator.cookieEnabled)return!1}else if(!kg.isEnabled())return!1;if(kg.h.cookie)return!0;S("embeds_web_enable_cookie_detection_fix")?kg.set("TESTCOOKIESENABLED","1",{Lb:60,Ne:"none",secure:!0}):kg.set("TESTCOOKIESENABLED","1",{Lb:60});if(kg.get("TESTCOOKIESENABLED")!=="1")return!1;kg.remove("TESTCOOKIESENABLED");return!0}
;var kn=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",kn);function ln(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=gn(this.h);a&&this.parse(a)}
var mn;function nn(){mn||(mn=new ln);return mn}
r=ln.prototype;r.get=function(a,b){on(a);pn(a);a=kn[a]!==void 0?kn[a].toString():null;return a!=null?a:b?b:""};
r.set=function(a,b){on(a);pn(a);if(b==null)throw Error("ExpectedNotNull");kn[a]=b.toString()};
function qn(a){return!!((rn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
r.remove=function(a){on(a);pn(a);delete kn[a]};
r.clear=function(){for(var a in kn)delete kn[a]};
function pn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function on(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function rn(a){a=kn[a]!==void 0?kn[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
r.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(kn[d]=c.toString())}};var sn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},tn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function un(){var a=C.navigator;return a?a.connection:void 0}
function vn(){var a=un();if(a){var b=sn[a.type||"unknown"]||"CONN_UNKNOWN";a=sn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function wn(){var a=un();if(a!=null&&a.effectiveType)return tn.hasOwnProperty(a.effectiveType)?tn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function U(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(qa(b))}
w(U,Error);function xn(){try{return yn(),!0}catch(a){return!1}}
function yn(a){if(R("DATASYNC_ID")!==void 0)return R("DATASYNC_ID");throw new U("Datasync ID not set",a===void 0?"unknown":a);}
;function zn(){}
function An(a,b){return Gj.Wa(a,0,b)}
zn.prototype.pa=function(a,b){return this.Wa(a,1,b)};
zn.prototype.Cb=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Bn=wm("web_emulated_idle_callback_delay",300),Cn=1E3/60-3,Dn=[8,5,4,3,2,1,0];
function En(a){a=a===void 0?{}:a;F.call(this);this.i=[];this.j={};this.Z=this.h=0;this.Y=this.u=!1;this.R=[];this.U=this.ga=!1;for(var b=z(Dn),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.wc=a.timeout||1;this.H=Cn;this.B=0;this.ta=this.De.bind(this);this.vc=this.lf.bind(this);this.Ab=this.Jd.bind(this);this.Bb=this.ke.bind(this);this.Tb=this.He.bind(this);this.Va=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!S("disable_scheduler_requestIdleCallback");(this.ja=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.ta)}
w(En,F);r=En.prototype;r.Cb=function(a){var b=Ya();Fn(this,a);a=Ya()-b;this.u||(this.H-=a)};
r.Wa=function(a,b,c){++this.Z;if(b===10)return this.Cb(a),this.Z;var d=this.Z;this.j[d]=a;this.u&&!c?this.R.push({id:d,priority:b}):(this.i[b].push(d),this.Y||this.u||(this.h!==0&&Gn(this)!==this.B&&this.stop(),this.start()));return d};
r.qa=function(a){delete this.j[a]};
function Hn(a){a.R.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
r.isHidden=function(){return!!document.hidden||!1};
function In(a){return!a.isHidden()&&a.ja}
function Gn(a){if(a.i[8].length){if(a.U)return 4;if(In(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?In(a)?3:2:1;return 0}
r.Ea=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function Fn(a,b){try{b()}catch(c){a.Ea(c)}}
function Jn(a){for(var b=z(Dn),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
r.ke=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ga=!0;Kn(this,b);this.ga=!1};
r.lf=function(){Kn(this)};
r.Jd=function(){Ln(this)};
r.He=function(a){this.U=!0;var b=Gn(this);b===4&&b!==this.B&&(this.stop(),this.start());Kn(this,void 0,a);this.U=!1};
r.De=function(){this.isHidden()||Ln(this);this.h&&(this.stop(),this.start())};
function Ln(a){a.stop();a.u=!0;for(var b=Ya(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Fn(a,e)}Mn(a);a.u=!1;Jn(a)&&a.start();b=Ya()-b;a.H-=b}
function Mn(a){for(var b=0,c=a.R.length;b<c;b++){var d=a.R[b];a.i[d.priority].push(d.id)}a.R.length=0}
function Kn(a,b,c){a.U&&a.B===4&&a.h||a.stop();a.u=!0;b=Ya()+(b||a.H);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ea(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Fn(a,f);d=a.ga?0:1;d=a.o>d?a.o:d;if(!(Ya()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Fn(a,c)}while(c&&Ya()<b)}a.u=!1;Mn(a);a.H=Cn;Jn(a)&&a.start()}
r.start=function(){this.Y=!1;if(this.h===0)switch(this.B=Gn(this),this.B){case 1:var a=this.Bb;this.h=this.Va?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Bn);break;case 2:this.h=window.setTimeout(this.vc,this.wc);break;case 3:this.h=window.requestAnimationFrame(this.Tb);break;case 4:this.h=window.setTimeout(this.Ab,0)}};
r.pause=function(){this.stop();this.Y=!0};
r.stop=function(){if(this.h){switch(this.B){case 1:var a=this.h;this.Va?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
r.aa=function(){Hn(this);this.stop();this.ja&&document.removeEventListener("visibilitychange",this.ta);F.prototype.aa.call(this)};var Nn=E("yt.scheduler.instance.timerIdMap_")||{},On=wm("kevlar_tuner_scheduler_soft_state_timer_ms",800),Pn=0,Qn=0;function Rn(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.da)a=new En(R("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Sn(){Tn();var a=E("ytglobal.schedulerInstanceInstance_");a&&(pc(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Tn(){Hn(Rn());for(var a in Nn)Nn.hasOwnProperty(a)&&delete Nn[Number(a)]}
function Un(a,b,c){if(!c)return c=c===void 0,-Rn().Wa(a,b,c);var d=window.setTimeout(function(){var e=Rn().Wa(a,b);Nn[d]=e},c);
return d}
function Vn(a){Rn().Cb(a)}
function Wn(a){var b=Rn();if(a<0)b.qa(-a);else{var c=Nn[a];c?(b.qa(c),delete Nn[a]):window.clearTimeout(a)}}
function Xn(){Yn()}
function Yn(){window.clearTimeout(Pn);Rn().start()}
function Zn(){Rn().pause();window.clearTimeout(Pn);Pn=window.setTimeout(Xn,On)}
function $n(){window.clearTimeout(Qn);Qn=window.setTimeout(function(){ao(0)},On)}
function ao(a){$n();var b=Rn();b.o=a;b.start()}
function bo(a){$n();var b=Rn();b.o>a&&(b.o=a,b.start())}
function co(){window.clearTimeout(Qn);var a=Rn();a.o=0;a.start()}
;function eo(){zn.apply(this,arguments)}
w(eo,zn);function fo(){eo.h||(eo.h=new eo);return eo.h}
eo.prototype.Wa=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):sm(a,c||0)};
eo.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
eo.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
eo.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var Gj=fo();
S("web_scheduler_auto_init")&&!E("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",Sn),D("yt.scheduler.instance.addJob",Un),D("yt.scheduler.instance.addImmediateJob",Vn),D("yt.scheduler.instance.cancelJob",Wn),D("yt.scheduler.instance.cancelAllJobs",Tn),D("yt.scheduler.instance.start",Yn),D("yt.scheduler.instance.pause",Zn),D("yt.scheduler.instance.setPriorityThreshold",ao),D("yt.scheduler.instance.enablePriorityThreshold",bo),D("yt.scheduler.instance.clearPriorityThreshold",co),D("yt.scheduler.initialized",
!0));function go(a){var b=new gk;this.h=(a=b.isAvailable()?a?new hk(b,a):b:null)?new bk(a):null;this.i=document.domain||window.location.hostname}
go.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Ni).serialize(b))}catch(f){return}else e=escape(b);fn(a,e,c,this.i)};
go.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=gn(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
go.prototype.remove=function(a){this.h&&this.h.remove(a);hn(a,"/",this.i)};var ho=function(){var a;return function(){a||(a=new go("ytidb"));return a}}();
function io(){var a;return(a=ho())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var jo=[],ko,lo=!1;function mo(){var a={};for(ko=new no(a.handleError===void 0?oo:a.handleError,a.logEvent===void 0?po:a.logEvent);jo.length>0;)switch(a=jo.shift(),a.type){case "ERROR":ko.Ea(a.payload);break;case "EVENT":ko.logEvent(a.eventType,a.payload)}}
function qo(a){lo||(ko?ko.Ea(a):(jo.push({type:"ERROR",payload:a}),jo.length>10&&jo.shift()))}
function ro(a,b){lo||(ko?ko.logEvent(a,b):(jo.push({type:"EVENT",eventType:a,payload:b}),jo.length>10&&jo.shift()))}
;function so(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function to(a){return a.substr(0,a.indexOf(":"))||a}
;var uo=cd||dd;function vo(a){var b=Nc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var wo={},xo=(wo.AUTH_INVALID="No user identifier specified.",wo.EXPLICIT_ABORT="Transaction was explicitly aborted.",wo.IDB_NOT_SUPPORTED="IndexedDB is not supported.",wo.MISSING_INDEX="Index not created.",wo.MISSING_OBJECT_STORES="Object stores not created.",wo.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",wo.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",wo.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
wo.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",wo.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",wo.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",wo.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",wo),yo={},zo=(yo.AUTH_INVALID="ERROR",yo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",yo.EXPLICIT_ABORT="IGNORED",yo.IDB_NOT_SUPPORTED="ERROR",yo.MISSING_INDEX=
"WARNING",yo.MISSING_OBJECT_STORES="ERROR",yo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",yo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",yo.QUOTA_EXCEEDED="WARNING",yo.QUOTA_MAYBE_EXCEEDED="WARNING",yo.UNKNOWN_ABORT="WARNING",yo.INCOMPATIBLE_DB_VERSION="WARNING",yo),Ao={},Bo=(Ao.AUTH_INVALID=!1,Ao.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Ao.EXPLICIT_ABORT=!1,Ao.IDB_NOT_SUPPORTED=!1,Ao.MISSING_INDEX=!1,Ao.MISSING_OBJECT_STORES=!1,Ao.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Ao.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Ao.QUOTA_EXCEEDED=!1,Ao.QUOTA_MAYBE_EXCEEDED=!0,Ao.UNKNOWN_ABORT=!0,Ao.INCOMPATIBLE_DB_VERSION=!1,Ao);function Co(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?xo[a]:c;d=d===void 0?zo[a]:d;e=e===void 0?Bo[a]:e;U.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Co.prototype)}
w(Co,U);function Do(a,b){Co.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},xo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Do.prototype)}
w(Do,Co);function Eo(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Eo.prototype)}
w(Eo,Error);var Fo=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Go(a,b,c,d){b=to(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Co)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Co("QUOTA_EXCEEDED",a);if(ed&&e.name==="UnknownError")return new Co("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Eo)return new Co("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Fo.some(function(f){return e.message.includes(f)}))return new Co("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Co("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",nd:e.name})];e.level="WARNING";return e}
function Ho(a,b,c){var d=io();return new Co("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Io(a){if(!a)throw Error();throw a;}
function Jo(a){return a}
function Ko(a){this.h=a}
function Lo(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=z(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=z(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Lo.all=function(a){return new Lo(new Ko(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={qb:0};f.qb<a.length;f={qb:f.qb},++f.qb)Lo.resolve(a[f.qb]).then(function(g){return function(h){d[g.qb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Lo.resolve=function(a){return new Lo(new Ko(function(b,c){a instanceof Lo?a.then(b,c):b(a)}))};
Lo.reject=function(a){return new Lo(new Ko(function(b,c){c(a)}))};
Lo.prototype.then=function(a,b){var c=this,d=a!=null?a:Jo,e=b!=null?b:Io;return new Lo(new Ko(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){Mo(c,c,d,f,g)}),c.i.push(function(){No(c,c,e,f,g)})):c.state.status==="FULFILLED"?Mo(c,c,d,f,g):c.state.status==="REJECTED"&&No(c,c,e,f,g)}))};
Lo.prototype.catch=function(a){return this.then(void 0,a)};
function Mo(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Lo?Oo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function No(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Lo?Oo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Oo(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Lo?Oo(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Po(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Qo(a){return new Promise(function(b,c){Po(a,b,c)})}
function Ro(a){return new Lo(new Ko(function(b,c){Po(a,b,c)}))}
;function So(a,b){return new Lo(new Ko(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var To=window,V=To.ytcsi&&To.ytcsi.now?To.ytcsi.now:To.performance&&To.performance.timing&&To.performance.now&&To.performance.timing.navigationStart?function(){return To.performance.timing.navigationStart+To.performance.now()}:function(){return(new Date).getTime()};function Uo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(V());this.i=!1}
r=Uo.prototype;r.add=function(a,b,c){return Vo(this,[a],{mode:"readwrite",la:!0},function(d){return d.objectStore(a).add(b,c)})};
r.clear=function(a){return Vo(this,[a],{mode:"readwrite",la:!0},function(b){return b.objectStore(a).clear()})};
r.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
r.count=function(a,b){return Vo(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).count(b)})};
function Wo(a,b,c){a=a.h.createObjectStore(b,c);return new Xo(a)}
r.delete=function(a,b){return Vo(this,[a],{mode:"readwrite",la:!0},function(c){return c.objectStore(a).delete(b)})};
r.get=function(a,b){return Vo(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).get(b)})};
function Yo(a,b,c){return Vo(a,[b],{mode:"readwrite",la:!0},function(d){d=d.objectStore(b);return Ro(d.h.put(c,void 0))})}
r.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Vo(a,b,c,d){var e,f,g,h,k,l,m,n,p,t,v,x;return A(function(y){switch(y.h){case 1:var G={mode:"readonly",la:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?G.mode=c:Object.assign(G,c);e=G;a.transactionCount++;f=e.la?3:1;g=0;case 2:if(h){y.F(4);break}g++;k=Math.round(V());ya(y,5);l=a.h.transaction(b,e.mode);G=y.yield;var I=new Zo(l);I=$o(I,d);return G.call(y,I,7);case 7:return m=y.i,n=Math.round(V()),ap(a,k,n,g,void 0,b.join(),e),y.return(m);case 5:p=za(y);t=Math.round(V());v=Go(p,
a.h.name,b.join(),a.h.version);if((x=v instanceof Co&&!v.h)||g>=f)ap(a,k,t,g,v,b.join(),e),h=v;y.F(2);break;case 4:return y.return(Promise.reject(h))}})}
function ap(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Co&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&ro("QUOTA_EXCEEDED",{dbName:to(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Co&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),ro("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),bp(a,!1,d,f,b,g.tag),qo(e)):bp(a,!0,d,f,b,g.tag)}
function bp(a,b,c,d,e,f){ro("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
r.getName=function(){return this.h.name};
function Xo(a){this.h=a}
r=Xo.prototype;r.add=function(a,b){return Ro(this.h.add(a,b))};
r.autoIncrement=function(){return this.h.autoIncrement};
r.clear=function(){return Ro(this.h.clear()).then(function(){})};
function cp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
r.count=function(a){return Ro(this.h.count(a))};
function dp(a,b){return ep(a,{query:b},function(c){return c.delete().then(function(){return fp(c)})}).then(function(){})}
r.delete=function(a){return a instanceof IDBKeyRange?dp(this,a):Ro(this.h.delete(a))};
r.get=function(a){return Ro(this.h.get(a))};
r.index=function(a){try{return new gp(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Eo(a,this.h.name);throw b;}};
r.getName=function(){return this.h.name};
r.keyPath=function(){return this.h.keyPath};
function ep(a,b,c){a=a.h.openCursor(b.query,b.direction);return hp(a).then(function(d){return So(d,c)})}
function Zo(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Co;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function $o(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return z(d).next().value})}
Zo.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Co("EXPLICIT_ABORT");};
Zo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Xo(a),this.i.set(a,b));return b};
function gp(a){this.h=a}
r=gp.prototype;r.count=function(a){return Ro(this.h.count(a))};
r.delete=function(a){return ip(this,{query:a},function(b){return b.delete().then(function(){return fp(b)})})};
r.get=function(a){return Ro(this.h.get(a))};
r.keyPath=function(){return this.h.keyPath};
r.unique=function(){return this.h.unique};
function ip(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return hp(a).then(function(d){return So(d,c)})}
function jp(a,b){this.request=a;this.cursor=b}
function hp(a){return Ro(a).then(function(b){return b?new jp(a,b):null})}
function fp(a){a.cursor.continue(void 0);return hp(a.request)}
jp.prototype.delete=function(){return Ro(this.cursor.delete()).then(function(){})};
jp.prototype.getValue=function(){return this.cursor.value};
jp.prototype.update=function(a){return Ro(this.cursor.update(a))};function kp(a,b,c){return new Promise(function(d,e){function f(){p||(p=new Uo(g.result,{closed:n}));return p}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Ld,k=c.blocking,l=c.jf,m=c.upgrade,n=c.closed,p;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&ro("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:to(a)});var v=f(),x=new Zo(g.transaction);
m&&m(v,function(y){return t.oldVersion<y&&t.newVersion>=y},x);
x.done.catch(function(y){e(y)})}catch(y){e(y)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){ro("IDB_UNEXPECTEDLY_CLOSED",{dbName:to(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function lp(a,b,c){c=c===void 0?{}:c;return kp(a,b,c)}
function mp(a,b){b=b===void 0?{}:b;var c,d,e,f;return A(function(g){if(g.h==1)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Ld)&&c.addEventListener("blocked",function(){e()}),g.yield(Qo(c),4);
if(g.h!=2)g.h=0,g.o=0;else throw f=za(g),Go(f,a,"",-1);})}
;function np(a,b){this.name=a;this.options=b;this.j=!0;this.D=this.o=0}
np.prototype.i=function(a,b,c){c=c===void 0?{}:c;return lp(a,b,c)};
np.prototype.delete=function(a){a=a===void 0?{}:a;return mp(this.name,a)};
function op(a,b){return new Co("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function pp(a,b){if(!b)throw Ho("openWithToken",to(a.name));return a.open()}
np.prototype.open=function(){function a(){var f,g,h,k,l,m,n,p,t,v;return A(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",ya(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var y=h=x.i,G=c.options,I=[],O=z(Object.keys(G.wb)),T=O.next();!T.done;T=O.next()){T=T.value;var Ja=G.wb[T],cb=Ja.Ie===void 0?Number.MAX_VALUE:Ja.Ie;!(y.h.version>=Ja.Db)||y.h.version>=cb||y.h.objectStoreNames.contains(T)||I.push(T)}k=I;if(k.length===0){x.F(5);break}l=Object.keys(c.options.wb);
m=h.objectStoreNames();if(c.D<wm("ytidb_reopen_db_retries",0))return c.D++,h.close(),qo(new Co("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.o<wm("ytidb_remake_db_retries",1))){x.F(6);break}c.o++;return x.yield(c.delete(),7);case 7:return qo(new Co("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new Do(m,l);case 5:return x.return(h);case 2:n=za(x);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){x.F(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:p=x.i;t=p.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw p.close(),c.j=!1,op(c,t);return x.return(p);case 8:throw b(),n instanceof
Error&&!S("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),Go(n,c.name,"",(v=c.options.version)!=null?v:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw op(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,jf:b,upgrade:this.options.upgrade};return this.h=d=a()};var qp=new np("YtIdbMeta",{wb:{databases:{Db:1}},upgrade:function(a,b){b(1)&&Wo(a,"databases",{keyPath:"actualName"})}});
function rp(a,b){var c;return A(function(d){if(d.h==1)return d.yield(pp(qp,b),2);c=d.i;return d.return(Vo(c,["databases"],{la:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Ro(f.h.put(a,void 0)).then(function(){})})}))})}
function sp(a,b){var c;return A(function(d){if(d.h==1)return a?d.yield(pp(qp,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function tp(a,b){var c,d;return A(function(e){return e.h==1?(c=[],e.yield(pp(qp,b),2)):e.h!=3?(d=e.i,e.yield(Vo(d,["databases"],{la:!0,mode:"readonly"},function(f){c.length=0;return ep(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return fp(g)})}),3)):e.return(c)})}
function up(a){return tp(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function vp(a,b,c){return tp(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function wp(a){var b,c;return A(function(d){if(d.h==1)return b=yn("YtIdbMeta hasAnyMeta other"),d.yield(tp(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var xp,yp=new function(){}(new function(){});
function zp(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=io();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=uo)f=/WebKit\/([0-9]+)/.exec(Nc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Nc()),f=!(f&&parseInt(f[1],10)>=602));if(f||Zc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(rp(d,yp),4);case 4:return e.yield(sp("yt-idb-test-do-not-use",yp),5);case 5:return e.return(!0);case 2:return za(e),e.return(!1)}})}
function Ap(){if(xp!==void 0)return xp;lo=!0;return xp=zp().then(function(a){lo=!1;var b;if((b=ho())!=null&&b.h){var c;b={hasSucceededOnce:((c=io())==null?void 0:c.hasSucceededOnce)||a};var d;(d=ho())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Bp(){return E("ytglobal.idbToken_")||void 0}
function Cp(){var a=Bp();return a?Promise.resolve(a):Ap().then(function(b){(b=b?yp:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var Dp=0;function Ep(a,b){Dp||(Dp=Gj.pa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(Cp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return h.yield(vp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.F(6);break}f=e[0];return h.yield(mp(f.actualName),7);case 7:return h.yield(sp(f.actualName,c),6);case 6:h.h=4;h.o=0;break;case 3:g=za(h),qo(g),d=!1;case 4:Gj.qa(Dp),Dp=0,d&&Ep(a,b),h.h=0}})}))}
function Fp(){var a;return A(function(b){return b.h==1?b.yield(Cp(),2):(a=b.i)?b.return(wp(a)):b.return(!1)})}
new rj;function Gp(a){if(!xn())throw a=new Co("AUTH_INVALID",{dbName:a}),qo(a),a;var b=yn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Hp(a,b,c,d){var e,f,g,h,k,l;return A(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Cp(),2);case 2:g=m.i;if(!g)throw h=Ho("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),qo(h),h;so(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Gp(a);ya(m,3);return m.yield(rp(k,g),5);case 5:return m.yield(lp(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=za(m),ya(m,7),m.yield(sp(k.actualName,
g),9);case 9:m.h=8;m.o=0;break;case 7:za(m);case 8:throw l;}})}
function Ip(a,b,c){c=c===void 0?{}:c;return Hp(a,b,!1,c)}
function Jp(a,b,c){c=c===void 0?{}:c;return Hp(a,b,!0,c)}
function Kp(a,b){b=b===void 0?{}:b;var c,d;return A(function(e){if(e.h==1)return e.yield(Cp(),2);if(e.h!=3){c=e.i;if(!c)return e.return();so(a);d=Gp(a);return e.yield(mp(d.actualName,b),3)}return e.yield(sp(d.actualName,c),0)})}
function Lp(a,b,c){a=a.map(function(d){return A(function(e){return e.h==1?e.yield(mp(d.actualName,b),2):e.yield(sp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Mp(){var a=a===void 0?{}:a;var b,c;return A(function(d){if(d.h==1)return d.yield(Cp(),2);if(d.h!=3){b=d.i;if(!b)return d.return();so("LogsDatabaseV2");return d.yield(up(b),3)}c=d.i;return d.yield(Lp(c,a,b),0)})}
function Np(a,b){b=b===void 0?{}:b;var c;return A(function(d){if(d.h==1)return d.yield(Cp(),2);if(d.h!=3){c=d.i;if(!c)return d.return();so(a);return d.yield(mp(a,b),3)}return d.yield(sp(a,c),0)})}
;function Op(a,b){np.call(this,a,b);this.options=b;so(a)}
w(Op,np);function Pp(a,b){var c;return function(){c||(c=new Op(a,b));return c}}
Op.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Jp:Ip)(a,b,Object.assign({},c))};
Op.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Np:Kp)(this.name,a)};
function Qp(a,b){return Pp(a,b)}
;var Rp={},Sp=Qp("ytGcfConfig",{wb:(Rp.coldConfigStore={Db:1},Rp.hotConfigStore={Db:1},Rp),shared:!1,upgrade:function(a,b){b(1)&&(cp(Wo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),cp(Wo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Tp(a){return pp(Sp(),a)}
function Up(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:V()},g.yield(Tp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Yo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Vp(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:V()},h.yield(Tp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Yo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Wp(a){var b,c;return A(function(d){return d.h==1?d.yield(Tp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Vo(b,["coldConfigStore"],{mode:"readwrite",la:!0},function(e){return ip(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Xp(a){var b,c;return A(function(d){return d.h==1?d.yield(Tp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Vo(b,["hotConfigStore"],{mode:"readwrite",la:!0},function(e){return ip(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Yp(){F.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(qa(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(Yp,F);Yp.prototype.aa=function(){for(var a=z(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;F.prototype.aa.call(this)};function Zp(){this.h=0;this.i=new Yp}
function $p(){var a;return(a=E("yt.gcf.config.hotConfigGroup"))!=null?a:R("RAW_HOT_CONFIG_GROUP")}
function aq(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.F(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=Bp();if(!d){g.F(3);break}if(c){g.F(4);break}return g.yield(Xp(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Up(c,b,d),3);case 3:if(c)for(var h=c,k=z(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function bq(a,b,c){var d,e,f,g;return A(function(h){if(h.h==1){if(!S("start_client_gcf"))return h.F(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Bp())?c?h.F(4):h.yield(Wp(d),5):h.F(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.F(0);g=c.configData;return h.yield(Vp(c,b,g,d),0)})}
function cq(){if(!Zp.h){var a=new Zp;Zp.h=a}a=Zp.h;var b=V()-a.h;if(!(a.h!==0&&b<wm("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=V());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
Zp.prototype.o=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function dq(){return"INNERTUBE_API_KEY"in Vl&&"INNERTUBE_API_VERSION"in Vl}
function eq(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),pe:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),gd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),qh:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),re:R("INNERTUBE_CONTEXT_HL"),qe:R("INNERTUBE_CONTEXT_GL"),se:R("INNERTUBE_HOST_OVERRIDE")||"",te:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),rh:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function fq(a){var b={client:{hl:a.re,gl:a.qe,clientName:a.gd,clientVersion:a.innertubeContextClientVersion,configInfo:a.pe}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=xm();c.length>0&&(b.request={internalExperimentFlags:c});c=a.gd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=an()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&((e=C.navigator)==null?0:e.deviceMemory)){var f;e=(f=C.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=vn())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&
(a=wn())&&b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=cq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=R("INNERTUBE_CONTEXT");var g;if(S("enable_persistent_device_token")&&(a==null?0:(g=a.client)==null?0:g.rolloutToken)){var h;b.client.rolloutToken=a==null?void 0:(h=a.client)==null?void 0:h.rolloutToken}g=Object;h=g.assign;a=b.client;f={};e=z(Object.entries(im(R("DEVICE",""))));for(d=e.next();!d.done;d=e.next())c=z(d.value),d=c.next().value,c=c.next().value,d==="cbrand"?f.deviceMake=c:d==="cmodel"?f.deviceModel=c:d==="cbr"?f.browserName=
c:d==="cbrver"?f.browserVersion=c:d==="cos"?f.osName=c:d==="cosver"?f.osVersion=c:d==="cplatform"&&(f.platform=c);b.client=h.call(g,a,f);return b}
function gq(a,b,c){c=c===void 0?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().hh:(a=dn(cn()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var hq=typeof TextEncoder!=="undefined"?new TextEncoder:null,iq=hq?function(a){return hq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function jq(a,b){this.version=a;this.args=b}
jq.prototype.serialize=function(){return{version:this.version,args:this.args}};function kq(a,b){this.topic=a;this.h=b}
kq.prototype.toString=function(){return this.topic};var lq=E("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Rb;M.prototype.publish=M.prototype.jb;M.prototype.clear=M.prototype.clear;D("ytPubsub2Pubsub2Instance",lq);var mq=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",mq);var nq=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",nq);var oq=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",oq);
D("ytPubsub2Pubsub2SkipSubKey",null);function pq(a,b){var c=qq();c&&c.publish.call(c,a.toString(),a,b)}
function rq(a){var b=sq,c=qq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(mq[d])try{if(f&&b instanceof kq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Bd){var l=new h;h.Bd=l.version}var m=h.Bd}catch(y){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var n=m.construct;
var p=k.args,t=p.length;if(t>0){var v=Array(t);for(k=0;k<t;k++)v[k]=p[k];var x=v}else x=[];f=n.call(m,h,x)}catch(y){throw y.message="yt.pubsub2.Data.deserialize(): "+y.message,y;}}catch(y){throw y.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+y.message,y;}a.call(window,f)}catch(y){am(y)}},oq[b.toString()]?E("yt.scheduler.instance")?Gj.pa(g):sm(g,0):g())});
mq[d]=!0;nq[b.toString()]||(nq[b.toString()]=[]);nq[b.toString()].push(d);return d}
function tq(){var a=uq,b=rq(function(c){a.apply(void 0,arguments);vq(b)});
return b}
function vq(a){var b=qq();b&&(typeof a==="number"&&(a=[a]),Kb(a,function(c){b.unsubscribeByKey(c);delete mq[c]}))}
function qq(){return E("ytPubsub2Pubsub2Instance")}
;function wq(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&pq("meta_logging_csi_event",{timerName:a,Jh:b})}
;var xq=void 0,yq=void 0;function zq(){yq||(yq=ul(R("WORKER_SERIALIZATION_URL")));return yq||void 0}
function Aq(){var a=zq();xq||a===void 0||(xq=new Worker(jb(a),void 0));return xq}
;var Bq=wm("max_body_size_to_compress",5E5),Cq=wm("min_body_size_to_compress",500),Dq=!0,Eq=0,Fq=0,Gq=wm("compression_performance_threshold_lr",250),Hq=wm("slow_compressions_before_abandon_count",4),Iq=!1,Jq=new Map,Kq=1,Lq=!0;function Mq(){if(typeof Worker==="function"&&zq()&&!Iq){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Jq.get(c.key);d&&(Nq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Jq.delete(c.key))}},b=Aq();
b&&(b.addEventListener("message",a),b.onerror=function(){Jq.clear()},Iq=!0)}}
function Oq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:V(),ticks:{},infos:{}};if(Dq)try{var g=Pq(b);if(g!=null&&(g>Bq||g<Cq))d(a,c);else{if(S("gzip_gel_with_worker")&&(S("initial_gzip_use_main_thread")&&!Lq||!S("initial_gzip_use_main_thread"))){Iq||Mq();var h=Aq();if(h&&!e){Jq.set(Kq,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Kq});Kq++;return}}var k=tl(iq(b));Nq(k,f,a,c,d)}}catch(l){bm(l),d(a,c)}else d(a,c)}
function Nq(a,b,c,d,e){Lq=!1;var f=V();b.ticks.gelc=f;Fq++;S("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Gq&&(Eq++,S("abandon_compression_after_N_slow_zips")?Fq===wm("compression_disable_point")&&Eq>Hq&&(Dq=!1):Dq=!1);Qq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Rq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=V(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(Dq&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Pq(g);if(h!=null&&(h>Bq||h<Cq))return a;c=b?{level:1}:void 0;f=tl(iq(g),c);var k=V();e.ticks.gelc=k;if(b){Fq++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Gq)if(Eq++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=Eq/Fq;var l=Hq/wm("compression_disable_point");Fq>0&&Fq%wm("compression_disable_point")===0&&b>=l&&(Dq=!1)}else Dq=!1;Qq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return bm(m),a}}else return a}
function Pq(a){try{return(new Blob(a.split(""))).size}catch(b){return bm(b),null}}
function Qq(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||wq("gel_compression",a,{sampleRate:.1})}
;function Sq(a){a=Object.assign({},a);delete a.Authorization;var b=og();if(b){var c=new Kj;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=hd(c.digest(),3)}return a}
;var Tq;function Uq(){Tq||(Tq=new go("yt.innertube"));return Tq}
function Vq(a,b,c,d){if(d)return null;d=Uq().get("nextId",!0)||1;var e=Uq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Sq(c),requestTime:Math.round(V())};Uq().set("nextId",d+1,86400,!0);Uq().set("requests",e,86400,!0);return d}
function Wq(a){var b=Uq().get("requests",!0)||{};delete b[a];Uq().set("requests",b,86400,!0)}
function Xq(a){var b=Uq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(V())-d.requestTime<6E4)){var e=d.authState,f=Sq(gq(!1));Cg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(V())),Yq(a,d.method,e,{}));delete b[c]}}Uq().set("requests",b,86400,!0)}}
;function Zq(a){this.Wb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ob=function(){};
this.now=Date.now;this.Gb=!1;var b;this.xd=(b=a.xd)!=null?b:100;var c;this.sd=(c=a.sd)!=null?c:1;var d;this.qd=(d=a.qd)!=null?d:2592E6;var e;this.pd=(e=a.pd)!=null?e:12E4;var f;this.rd=(f=a.rd)!=null?f:5E3;var g;this.V=(g=a.V)!=null?g:void 0;this.cc=!!a.cc;var h;this.Zb=(h=a.Zb)!=null?h:.1;var k;this.nc=(k=a.nc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.ob&&(this.ob=a.ob);a.Gb&&(this.Gb=a.Gb);a.Wb&&(this.Wb=a.Wb);this.W=a.W;this.Ca=a.Ca;this.fa=a.fa;this.ea=a.ea;this.sendFn=a.sendFn;
this.Lc=a.Lc;this.Ic=a.Ic;$q(this)&&(!this.W||this.W("networkless_logging"))&&ar(this)}
function ar(a){$q(a)&&!a.Gb&&(a.h=!0,a.cc&&Math.random()<=a.Zb&&a.fa.Pd(a.V),br(a),a.ea.wa()&&a.Qb(),a.ea.listen(a.Lc,a.Qb.bind(a)),a.ea.listen(a.Ic,a.Vc.bind(a)))}
r=Zq.prototype;r.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if($q(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.fa.set(d,this.V).then(function(e){d.id=e;c.ea.wa()&&cr(c,d)}).catch(function(e){cr(c,d);
dr(c,e)})}else this.sendFn(a,b)};
r.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if($q(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W&&this.W("nwl_skip_retry")&&(e.skipRetry=c);if(this.ea.wa()||this.W&&this.W("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(k.h==1)return k.yield(d.fa.set(e,d.V).catch(function(l){dr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.fa.set(e,this.V).catch(function(g){d.sendFn(a,b,e.skipRetry);
dr(d,g)})}else this.sendFn(a,b,this.W&&this.W("nwl_skip_retry")&&c)};
r.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if($q(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.fa.nb(d.id,c.V):e=!0;c.ea.bb&&c.W&&c.W("vss_network_hint")&&c.ea.bb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.fa.set(d,this.V).then(function(g){d.id=g;e&&c.fa.nb(d.id,c.V)}).catch(function(g){dr(c,g)})}else this.sendFn(a,b,void 0,!0)};
r.Qb=function(){var a=this;if(!$q(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ca.pa(function(){var b;return A(function(c){if(c.h==1)return c.yield(a.fa.cd("NEW",a.V),2);if(c.h!=3)return b=c.i,b?c.yield(cr(a,b),3):(a.Vc(),c.return());a.i&&(a.i=0,a.Qb());c.h=0})},this.xd))};
r.Vc=function(){this.Ca.qa(this.i);this.i=0};
function cr(a,b){var c;return A(function(d){switch(d.h){case 1:if(!$q(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.F(2);break}return d.yield(a.fa.xe(b.id,a.V),3);case 3:(c=d.i)||a.ob(Error("The request cannot be found in the database."));case 2:if(er(a,b,a.qd)){d.F(4);break}a.ob(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.F(5);break}return d.yield(a.fa.nb(b.id,a.V),5);case 5:return d.return();case 4:b.skipRetry||(b=fr(a,
b));if(!b){d.F(0);break}if(!b.skipRetry||b.id===void 0){d.F(8);break}return d.yield(a.fa.nb(b.id,a.V),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function fr(a,b){if(!$q(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(m){switch(m.h){case 1:g=gr(f);(h=hr(f))&&a.W&&a.W("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.W&&a.W("nwl_consider_error_code")&&g||a.W&&!a.W("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.nc)){m.F(2);break}if(!a.ea.sc){m.F(3);break}return m.yield(a.ea.sc(),3);case 3:if(a.ea.wa()){m.F(2);break}c(e,f);if(!a.W||!a.W("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.F(6);
break}return m.yield(a.fa.Mc(b.id,a.V,!1),6);case 6:return m.return();case 2:if(a.W&&a.W("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.nc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.F(8);break}return b.sendCount<a.sd?m.yield(a.fa.Mc(b.id,a.V,!0,h?!1:void 0),12):m.yield(a.fa.nb(b.id,a.V),8);case 12:a.Ca.pa(function(){a.ea.wa()&&a.Qb()},a.rd);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.F(2):h.yield(a.fa.nb(b.id,a.V),2);a.ea.bb&&a.W&&a.W("vss_network_hint")&&a.ea.bb(!0);d(e,f);h.h=0})};
return b}
function er(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function br(a){if(!$q(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.fa.cd("QUEUED",a.V).then(function(b){b&&!er(a,b,a.pd)?a.Ca.pa(function(){return A(function(c){if(c.h==1)return b.id===void 0?c.F(2):c.yield(a.fa.Mc(b.id,a.V),2);br(a);c.h=0})}):a.ea.wa()&&a.Qb()})}
function dr(a,b){a.Ed&&!a.ea.wa()?a.Ed(b):a.handleError(b)}
function $q(a){return!!a.V||a.Wb}
function gr(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function hr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var ir;
function jr(){if(ir)return ir();var a={};ir=Qp("LogsDatabaseV2",{wb:(a.LogsRequestsStore={Db:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&Wo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),cp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return ir()}
;function kr(a){return pp(jr(),a)}
function lr(a,b){var c,d,e,f;return A(function(g){if(g.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(kr(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Yo(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=V();mr(c);return g.return(f)})}
function nr(a,b){var c,d,e,f,g,h,k,l;return A(function(m){if(m.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(kr(b),2);if(m.h!=3)return d=m.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,V()],h=IDBKeyRange.bound(f,g),k="prev",S("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Vo(d,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(n){return ip(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(p){p.getValue()&&(l=p.getValue(),a==="NEW"&&(l.status="QUEUED",p.update(l)))})}),3);
c.ticks.tc=V();mr(c);return m.return(l)})}
function or(a,b){var c;return A(function(d){if(d.h==1)return d.yield(kr(b),2);c=d.i;return d.return(Vo(c,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Ro(f.h.put(g,void 0)).then(function(){return g})})}))})}
function pr(a,b,c,d){c=c===void 0?!0:c;var e;return A(function(f){if(f.h==1)return f.yield(kr(b),2);e=f.i;return f.return(Vo(e,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Ro(h.h.put(k,void 0)).then(function(){return k})):Lo.resolve(void 0)})}))})}
function qr(a,b){var c;return A(function(d){if(d.h==1)return d.yield(kr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function rr(a){var b,c;return A(function(d){if(d.h==1)return d.yield(kr(a),2);b=d.i;c=V()-2592E6;return d.yield(Vo(b,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){return ep(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return fp(f)})})}),0)})}
function sr(){A(function(a){return a.yield(Mp(),0)})}
function mr(a){S("nwl_csi_killswitch")||wq("networkless_performance",a,{sampleRate:1})}
;var tr={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrCowatchUserStartOrJoinEvent:504,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,
mbsConnectionInitiated:138,mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,
kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,parentCodeEvent:502,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,
mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,
cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,
webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,shortsCreationFallbackEvent:493,vssData:491,castMatch:494,
miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503,innertubeResponseCacheMetrics:505,miniAppAdEvent:506,dataPlanUpsellEvent:507};var ur={},vr=Qp("ServiceWorkerLogsDatabase",{wb:(ur.SWHealthLog={Db:1},ur),shared:!0,upgrade:function(a,b){b(1)&&cp(Wo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function wr(a){return pp(vr(),a)}
function xr(a){var b,c;A(function(d){if(d.h==1)return d.yield(wr(a),2);b=d.i;c=V()-2592E6;return d.yield(Vo(b,["SWHealthLog"],{mode:"readwrite",la:!0},function(e){return ep(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return fp(f)})})}),0)})}
function yr(a){var b;return A(function(c){if(c.h==1)return c.yield(wr(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var zr={},Ar=0;function Br(a){var b=new Image,c=""+Ar++;zr[c]=b;b.onload=b.onerror=function(){delete zr[c]};
b.src=a}
;var Cr;function Dr(){Cr||(Cr=new go("yt.offline"));return Cr}
function Er(a){if(S("offline_error_handling")){var b=Dr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Dr().set("errors",b,2592E3,!0)}}
;function Fr(){this.h=new Map;this.i=!1}
function Gr(){if(!Fr.h){var a=E("yt.networkRequestMonitor.instance")||new Fr;D("yt.networkRequestMonitor.instance",a);Fr.h=a}return Fr.h}
Fr.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Fr.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Fr.prototype.removeParams=function(a){return a.split("?")[0]};
Fr.prototype.removeParams=Fr.prototype.removeParams;Fr.prototype.isEndpointCFR=Fr.prototype.isEndpointCFR;Fr.prototype.requestComplete=Fr.prototype.requestComplete;Fr.getInstance=Gr;function Hr(){ai.call(this);var a=this;this.j=!1;this.i=Fj();this.i.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=Dr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new U(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;am(d)}Dr().set("errors",{},2592E3,!0)}}})}
w(Hr,ai);function Ir(){if(!Hr.h){var a=E("yt.networkStatusManager.instance")||new Hr;D("yt.networkStatusManager.instance",a);Hr.h=a}return Hr.h}
r=Hr.prototype;r.wa=function(){return this.i.wa()};
r.bb=function(a){this.i.i=a};
r.ge=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
r.Wd=function(){this.j=!0};
r.listen=function(a,b){return this.i.listen(a,b)};
r.sc=function(a){a=Dj(this.i,a);a.then(function(b){S("use_cfr_monitor")&&Gr().requestComplete("generate_204",b)});
return a};
Hr.prototype.sendNetworkCheckRequest=Hr.prototype.sc;Hr.prototype.listen=Hr.prototype.listen;Hr.prototype.enableErrorFlushing=Hr.prototype.Wd;Hr.prototype.getWindowStatus=Hr.prototype.ge;Hr.prototype.networkStatusHint=Hr.prototype.bb;Hr.prototype.isNetworkAvailable=Hr.prototype.wa;Hr.getInstance=Ir;function Jr(a){a=a===void 0?{}:a;ai.call(this);var b=this;this.i=this.u=0;this.j=Ir();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Kr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Kr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){bi(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){bi(b,"publicytnetworkstatus-offline")})))}
w(Jr,ai);Jr.prototype.wa=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Jr.prototype.bb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Jr.prototype.sc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&Gr().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.bb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.wa())})):c?d.return(c(a)):d.return(!0)})};
function Kr(a,b){a.rateLimit?a.i?(Gj.qa(a.u),a.u=Gj.pa(function(){a.o!==b&&(bi(a,b),a.o=b,a.i=V())},a.rateLimit-(V()-a.i))):(bi(a,b),a.o=b,a.i=V()):bi(a,b)}
;var Lr;function Mr(){var a=Zq.call;Lr||(Lr=new Jr({wh:!0,nh:!0}));a.call(Zq,this,{fa:{Pd:rr,nb:qr,cd:nr,xe:or,Mc:pr,set:lr},ea:Lr,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;bm(new U(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else am(b)},
ob:bm,sendFn:Rr,now:V,Ed:Er,Ca:fo(),Lc:"publicytnetworkstatus-online",Ic:"publicytnetworkstatus-offline",cc:!0,Zb:.1,nc:wm("potential_esf_error_limit",10),W:S,Gb:!(xn()&&Sr())});this.j=new rj;S("networkless_immediately_drop_all_requests")&&sr();Np("LogsDatabaseV2")}
w(Mr,Zq);function Tr(){var a=E("yt.networklessRequestController.instance");a||(a=new Mr,D("yt.networklessRequestController.instance",a),S("networkless_logging")&&Cp().then(function(b){a.V=b;ar(a);a.j.resolve();a.cc&&Math.random()<=a.Zb&&a.V&&xr(a.V);S("networkless_immediately_drop_sw_health_store")&&Ur(a)}));
return a}
Mr.prototype.writeThenSend=function(a,b){b||(b={});b=Vr(a,b);xn()||(this.h=!1);Zq.prototype.writeThenSend.call(this,a,b)};
Mr.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Vr(a,b);xn()||(this.h=!1);Zq.prototype.sendThenWrite.call(this,a,b,c)};
Mr.prototype.sendAndWrite=function(a,b){b||(b={});b=Vr(a,b);xn()||(this.h=!1);Zq.prototype.sendAndWrite.call(this,a,b)};
Mr.prototype.awaitInitialization=function(){return this.j.promise};
function Ur(a){var b;A(function(c){if(!a.V)throw b=Ho("clearSWHealthLogsDb"),b;return c.return(yr(a.V).catch(function(d){a.handleError(d)}))})}
function Rr(a,b,c,d){d=d===void 0?!1:d;b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&Wr(a,b);if(S("use_request_time_ms_header"))b.headers&&mm(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(V())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Bm(a,void 0,"POST",f,void 0);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Bm(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new ab({url:a});if(k.j&&k.i||k.o){var l=Yb(Zb(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var n=a.search(hc),p=fc(a,0,"ri",n);if(p<0)var t=null;else{var v=a.indexOf("&",p);if(v<0||v>n)v=n;t=decodeURIComponent(a.slice(p+3,v!==-1?v:0).replace(/\+/g," "))}m=t!=="1"}var x=!m;break b}}catch(G){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(G){}y=!1}c=y?!0:!1}else c=
!1;c||Br(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Oq(a,b.postBody,b,Fm,d)):Oq(a,JSON.stringify(b.postParams),b,Em,d):Fm(a,b)}
function Vr(a,b){S("use_event_time_ms_header")&&mm(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(V())));return b}
function Wr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Gr().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Gr().requestComplete(a,!0);d(e,f)}}
function Sr(){return $b(document.location.toString())!=="www.youtube-nocookie.com"}
;var Xr=!1,Yr=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Xr};D("ytNetworklessLoggingInitializationOptions",Yr);function Zr(){var a;A(function(b){if(b.h==1)return b.yield(Cp(),2);a=b.i;if(!a||!xn()&&!S("nwl_init_require_datasync_id_killswitch")||!Sr())return b.F(0);Xr=!0;Yr.isNwlInitialized=Xr;return b.yield(Tr().awaitInitialization(),0)})}
;function $r(a){var b=this;this.config_=null;a?this.config_=a:dq()&&(this.config_=eq());An(function(){Xq(b)},5E3)}
$r.prototype.isReady=function(){!this.config_&&dq()&&(this.config_=eq());return!!this.config_};
function Yq(a,b,c,d){function e(n){n=n===void 0?!1:n;var p;if(d.retry&&h!="www.youtube-nocookie.com"&&(n||S("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(p=Vq(b,c,l,k)),p)){var t=g.onSuccess,v=g.onFetchSuccess;g.onSuccess=function(G,I){Wq(p);t(G,I)};
c.onFetchSuccess=function(G,I){Wq(p);v(G,I)}}try{if(n&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Tr().writeThenSend(m,g):Tr().sendAndWrite(m,g);
else if(d.compress){var x=!d.networklessOptions.writeThenSend;if(g.postBody){var y=g.postBody;typeof y!=="string"&&(y=JSON.stringify(g.postBody));Oq(m,y,g,Fm,x)}else Oq(m,JSON.stringify(g.postParams),g,Em,x)}else S("web_all_payloads_via_jspb")?Fm(m,g):Em(m,g)}catch(G){if(G.name==="InvalidAccessError")p&&(Wq(p),p=0),bm(Error("An extension is blocking network request."));else throw G;}p&&An(function(){Xq(a)},5E3)}
!R("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&bm(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new U("innertube xhrclient not ready",b,c,d);am(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,p){if(d.onSuccess)d.onSuccess(p)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,p){if(d.onError)d.onError(p)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.se)&&(h=f);var k=a.config_.te||!1,l=gq(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m=km(""+h+("/youtubei/"+a.config_.innertubeApiVersion+"/"+b),{alt:"json"});(E("ytNetworklessLoggingInitializationOptions")?Yr.isNwlInitialized:Xr)?Ap().then(function(n){e(n)}):e(!1)}
;var as=0,bs=ad?"webkit":$c?"moz":Yc?"ms":Xc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++as});var cs={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function ds(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in cs||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function es(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
ds.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
ds.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
ds.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var yg=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",yg);var gs=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",gs);
function hs(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return xg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Qa(e[4])&&Qa(d)&&Cg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function is(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=hs(a,b,c,d);if(e)return e;e=++gs.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new ds(h);if(!Lg(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new ds(h);
h.currentTarget=a;return c.call(a,h)};
g=$l(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),js()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);yg[e]=[a,b,c,g,d];return e}
function ks(a){a&&(typeof a=="string"&&(a=[a]),Kb(a,function(b){if(b in yg){var c=yg[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?js()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete yg[b]}}))}
var js=qi(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function ls(a){this.H=a;this.h=null;this.o=0;this.B=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.U=is(window,"mousemove",Wa(this.Y,this));a=Wa(this.R,this);typeof a==="function"&&(a=$l(a));this.Z=window.setInterval(a,25)}
Za(ls,F);ls.prototype.Y=function(a){a.h===void 0&&es(a);var b=a.h;a.i===void 0&&es(a);this.h=new ug(b,a.i)};
ls.prototype.R=function(){if(this.h){var a=V();if(this.o!=0){var b=this.B,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.H();this.u=d}this.o=a;this.B=this.h;this.j=(this.j+1)%4}};
ls.prototype.aa=function(){window.clearInterval(this.Z);ks(this.U)};var ms={};
function ns(a){var b=a===void 0?{}:a;a=b.Fe===void 0?!1:b.Fe;b=b.Xd===void 0?!0:b.Xd;if(E("_lact",window)==null){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);c==-1&&ps();is(document,"keydown",ps);is(document,"keyup",ps);is(document,"mousedown",ps);is(document,"mouseup",ps);a?is(window,"touchmove",function(){qs("touchmove",200)},{passive:!0}):(is(window,"resize",function(){qs("resize",200)}),b&&is(window,"scroll",function(){qs("scroll",200)}));
new ls(function(){qs("mouse",100)});
is(document,"touchstart",ps,{passive:!0});is(document,"touchend",ps,{passive:!0})}}
function qs(a,b){ms[a]||(ms[a]=!0,Gj.pa(function(){ps();ms[a]=!1},b))}
function ps(){E("_lact",window)==null&&ns();var a=Date.now();D("_lact",a,window);E("_fact",window)==-1&&D("_fact",a,window);(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function rs(){var a=E("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var ss=C.ytPubsubPubsubInstance||new M,ts=C.ytPubsubPubsubSubscribedKeys||{},us=C.ytPubsubPubsubTopicToKeys||{},vs=C.ytPubsubPubsubIsSynchronous||{};function ws(a,b){var c=xs();if(c&&b){var d=c.subscribe(a,function(){function e(){ts[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{vs[a]?e():sm(e,0)}catch(g){am(g)}},void 0);
ts[d]=!0;us[a]||(us[a]=[]);us[a].push(d);return d}return 0}
function ys(a){var b=xs();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Kb(a,function(c){b.unsubscribeByKey(c);delete ts[c]}))}
function zs(a,b){var c=xs();c&&c.publish.apply(c,arguments)}
function As(a){var b=xs();if(b)if(b.clear(a),a)Bs(a);else for(var c in us)Bs(c)}
function xs(){return C.ytPubsubPubsubInstance}
function Bs(a){us[a]&&(a=us[a],Kb(a,function(b){ts[b]&&delete ts[b]}),a.length=0)}
M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Rb;M.prototype.publish=M.prototype.jb;M.prototype.clear=M.prototype.clear;D("ytPubsubPubsubInstance",ss);D("ytPubsubPubsubTopicToKeys",us);D("ytPubsubPubsubIsSynchronous",vs);D("ytPubsubPubsubSubscribedKeys",ts);var Cs=Symbol("injectionDeps");function Ds(a){this.name=a}
Ds.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Es(a){this.key=a}
function Fs(){this.i=new Map;this.j=new Map;this.h=new Map}
function Gs(a,b){a.i.set(b.pc,b);var c=a.j.get(b.pc);if(c)try{c.Fh(a.resolve(b.pc))}catch(d){c.Dh(d)}}
Fs.prototype.resolve=function(a){return a instanceof Es?Hs(this,a.key,[],!0):Hs(this,a,[])};
function Hs(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Ad!==void 0)var e=d.Ad;else if(d.rf)e=d[Cs]?Is(a,d[Cs],c):[],e=d.rf.apply(d,qa(e));else if(d.zd){e=d.zd;var f=e[Cs]?Is(a,e[Cs],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(qa(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Ih||a.h.set(b,e);return e}
function Is(a,b,c){return b?b.map(function(d){return d instanceof Es?Hs(a,d.key,c,!0):Hs(a,d,c)}):[]}
;var Js;function Ks(){Js||(Js=new Fs);return Js}
;var Ls=window;function Ms(){var a,b;return"h5vcc"in Ls&&((a=Ls.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Ls.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Ls&&Ls.performance.mark&&Ls.performance.measure?2:0}
function Ns(a){var b=Ms();switch(b){case 1:Ls.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Ls.performance.mark(a+"-start");break;case 0:break;default:Bb(b,"unknown trace type")}}
function Os(a){var b=Ms();switch(b){case 1:Ls.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Ls.performance.mark(c);Ls.performance.measure(a,b,c);break;case 0:break;default:Bb(b,"unknown trace type")}}
;var Ps=S("web_enable_lifecycle_monitoring")&&Ms()!==0,Qs=S("web_enable_lifecycle_monitoring");function Rs(a){var b,c;(c=(b=window).onerror)==null||c.call(b,a.message,"",0,0,a)}
;function Ss(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?fo():d;this.j=c;this.scheduler=d;this.i=new rj;this.h=a;for(a={Ya:0};a.Ya<this.h.length;a={lc:void 0,Ya:a.Ya},a.Ya++)a.lc=this.h[a.Ya],c=function(e){return function(){e.lc.Bc();b.h[e.Ya].oc=!0;b.h.every(function(f){return f.oc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.lc),d=this.scheduler.Wa(c,d),this.h[a.Ya]=Object.assign({},a.lc,{Bc:c,
jobId:d})}
function Ts(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=z(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.oc||(a.scheduler.qa(c.jobId),a.scheduler.Wa(c.Bc,10))}
Ss.prototype.cancel=function(){for(var a=z(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.oc||this.scheduler.qa(b.jobId),b.oc=!0;this.i.resolve()};
Ss.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Us(a){this.state=a;this.plugins=[];this.o=void 0;this.B={};Ps&&Ns(this.state)}
r=Us.prototype;r.install=function(a){this.plugins.push(a);return this};
r.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
r.transition=function(a,b){var c=this;Ps&&Os(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Ts(this.j),this.j=void 0);Vs(this,a,b);this.state=a;Ps&&Ns(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ws(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ws(a,b){var c=b.filter(function(e){return Xs(a,e)===10}),d=b.filter(function(e){return Xs(a,e)!==10});
return a.B.Hh?function(){var e=B.apply(0,arguments);return A(function(f){if(f.h==1)return f.yield(a.Le.apply(a,[c].concat(qa(e))),2);a.ud.apply(a,[d].concat(qa(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Me.apply(a,[c].concat(qa(e)));a.ud.apply(a,[d].concat(qa(e)))}}
r.Me=function(a){for(var b=B.apply(1,arguments),c=fo(),d=z(a),e=d.next(),f={};!e.done;f={Ib:void 0},e=d.next())f.Ib=e.value,c.Cb(function(g){return function(){Ys(g.Ib.name);Zs(function(){return g.Ib.callback.apply(g.Ib,qa(b))});
$s(g.Ib.name)}}(f))};
r.Le=function(a){var b=B.apply(1,arguments),c,d,e,f,g;return A(function(h){h.h==1&&(c=fo(),d=z(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.F(0);f.Ra=e.value;f.Ub=void 0;g=function(k){return function(){Ys(k.Ra.name);var l=Zs(function(){return k.Ra.callback.apply(k.Ra,qa(b))});
ae(l)?k.Ub=S("web_lifecycle_error_handling_killswitch")?l.then(function(){$s(k.Ra.name)}):l.then(function(){$s(k.Ra.name)},function(m){Rs(m);
$s(k.Ra.name)}):$s(k.Ra.name)}}(f);
c.Cb(g);return f.Ub?h.yield(f.Ub,3):h.F(3)}f={Ra:void 0,Ub:void 0};e=d.next();return h.F(2)})};
r.ud=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{Bc:function(){Ys(e.name);Zs(function(){return e.callback.apply(e,qa(b))});
$s(e.name)},
priority:Xs(c,e)}});
d.length&&(this.j=new Ss(d))};
function Xs(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function Ys(a){Ps&&a&&Ns(a)}
function $s(a){Ps&&a&&Os(a)}
function Vs(a,b,c){Qs&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
ea.Object.defineProperties(Us.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});
function Zs(a){if(S("web_lifecycle_error_handling_killswitch"))return a();try{return a()}catch(b){Rs(b)}}
;function at(a){Us.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.D},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var bt;w(at,Us);at.prototype.i=function(a,b){var c=this;this.h=An(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
at.prototype.D=function(a,b){this.h&&(Gj.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function ct(){bt||(bt=new at);return bt}
;var dt=[];D("yt.logging.transport.getScrapedGelPayloads",function(){return dt});function et(){this.store={};this.h={}}
et.prototype.storePayload=function(a,b){a=ft(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);S("more_accurate_gel_parser")&&(b=new CustomEvent("TRANSPORTING_NEW_EVENT"),window.dispatchEvent(b));return a};
et.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=gt(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,qa(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,qa(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,qa(this.smartExtractMatchingEntries(a))));return c};
et.prototype.extractMatchingEntries=function(a){a=gt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,qa(this.store[a[c]])),delete this.store[a[c]]);return b};
et.prototype.getSequenceCount=function(a){a=gt(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function gt(a,b){var c=ft(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&ft(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(ht(b.auth,g[0])){var h=b.isJspb;ht(h===void 0?"undefined":h?"true":"false",g[1])&&ht(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),ht(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function ht(a,b){return a===void 0||a==="undefined"?!0:a===b}
et.prototype.getSequenceCount=et.prototype.getSequenceCount;et.prototype.extractMatchingEntries=et.prototype.extractMatchingEntries;et.prototype.smartExtractMatchingEntries=et.prototype.smartExtractMatchingEntries;et.prototype.storePayload=et.prototype.storePayload;function ft(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function jt(a,b){if(a)return a[b.name]}
;var kt=wm("initial_gel_batch_timeout",2E3),lt=wm("gel_queue_timeout_max_ms",6E4),mt=wm("gel_min_batch_size",5),nt=void 0;function ot(){this.o=this.h=this.i=0;this.j=!1}
var pt=new ot,qt=new ot,rt=new ot,st=new ot,tt,ut=!0,vt=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",vt);var wt={};function xt(){var a=E("yt.logging.ims");a||(a=new et,D("yt.logging.ims",a));return a}
function zt(a,b){if(a.endpoint==="log_event"){At();var c=Bt(a),d=Ct(a.payload)||"";a:{if(S("enable_web_tiered_gel")){var e=tr[d||""];var f,g,h,k=Ks().resolve(new Es(Zp))==null?void 0:(f=$p())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!S("web_payload_policy_disabled_killswitch"))return;k=Dt(e.tier);if(k===400){Et(a,b);return}}wt[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};xt().storePayload(e,a.payload);Ft(b,c,e,d==="gelDebuggingEvent")}}
function Ft(a,b,c,d){function e(){Gt({writeThenSend:!0},S("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=f===void 0?!1:f;d=d===void 0?!1:d;a&&(nt=new a);a=wm("tvhtml5_logging_max_batch_ads_fork")||wm("tvhtml5_logging_max_batch")||wm("web_logging_max_batch")||100;var g=V(),h=Ht(f,c.tier),k=h.o;d&&(h.j=!0);d=0;c&&(d=xt().getSequenceCount(c));d>=1E3?e():d>=a?tt||(tt=It(function(){e();tt=void 0},0)):g-k>=10&&(Jt(f,c.tier),h.o=g)}
function Et(a,b){if(a.endpoint==="log_event"){S("more_accurate_gel_parser")&&xt().storePayload({isJspb:!1},a.payload);At();var c=Bt(a),d=new Map;d.set(c,[a.payload]);var e=Ct(a.payload)||"";b&&(nt=new b);return new ri(function(f,g){nt&&nt.isReady()?Kt(d,nt,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Bt(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);vt[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Gt(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new ri(function(e,f){var g=Ht(c,d),h=g.j;g.j=!1;Lt(g.i);Lt(g.h);g.h=0;nt&&nt.isReady()?d===void 0&&S("enable_web_tiered_gel")?Mt(e,f,a,b,c,300,h):Mt(e,f,a,b,c,d,h):(Jt(c,d),e())})}
function Mt(a,b,c,d,e,f,g){var h=nt;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=S("enable_web_tiered_gel")?xt().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):xt().extractMatchingEntries(e),k.set(d,f);else for(d=z(Object.keys(wt)),l=d.next();!l.done;l=d.next())l=l.value,e=S("enable_web_tiered_gel")?xt().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):xt().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete wt[l];Kt(k,h,a,b,c,!1,g)}
function Jt(a,b){function c(){Gt({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Ht(a,b),e=d===st||d===rt?5E3:lt;S("web_gel_timeout_cap")&&!d.h&&(e=It(function(){c()},e),d.h=e);
Lt(d.i);e=R("LOGGING_BATCH_TIMEOUT",wm("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&ut&&(e=kt);e=It(function(){wm("gel_min_batch_size")>0?xt().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=mt&&c():c()},e);
d.i=e}
function Kt(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(V()),k=a.size,l=(g===void 0?0:g)&&S("vss_through_gel_video_stats")?"video_stats":"log_event";a=z(a);var m=a.next();for(g={};!m.done;g={Hc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Kc:void 0,Jc:void 0},m=a.next()){var n=z(m.value);m=n.next().value;n=n.next().value;g.batchRequest=Eg({context:fq(b.config_||eq())});if(!Pa(n)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=vt[m])&&
Nt(g.batchRequest,m,n);delete vt[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Ot(g.batchRequest,h,g.dangerousLogToVisitorSession);S("always_send_and_write")&&(e.writeThenSend=!1);g.Kc=function(p){S("start_client_gcf")&&Gj.pa(function(){return A(function(t){return t.yield(Pt(p),0)})});
k--;k||c()};
g.Hc=0;g.Jc=function(p){return function(){p.Hc++;if(e.bypassNetworkless&&p.Hc===1)try{Yq(b,l,p.batchRequest,Qt({writeThenSend:!0},p.dangerousLogToVisitorSession,p.Kc,p.Jc,f)),ut=!1}catch(t){am(t),d()}k--;k||c()}}(g);
try{Yq(b,l,g.batchRequest,Qt(e,g.dangerousLogToVisitorSession,g.Kc,g.Jc,f)),ut=!1}catch(p){am(p),d()}}}
function Qt(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,ih:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};Rt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));return a}
function Ot(a,b,c){Rt()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),Wl("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Nt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function At(){var a;(a=E("yt.logging.transport.enableScrapingForTest"))||(a=um("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(dt=[],D("yt.logging.transport.enableScrapingForTest",!0),D("yt.logging.transport.scrapedPayloadsForTesting",dt),D("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),D("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
D("yt.logging.transport.scrapeClientEvent",!0))}
function Rt(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function It(a,b){return S("transport_use_scheduler")===!1?sm(a,b):S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?An(function(){if(ct().currentState==="none")a();else{var c={};ct().install((c.none={callback:a},c))}},b):An(a,b)}
function Lt(a){S("transport_use_scheduler")?Gj.qa(a):window.clearTimeout(a)}
function Pt(a){var b,c,d,e,f,g,h,k,l,m;return A(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=jt(d,yl),g=(f=d)==null?void 0:f.hotHashData,h=jt(d,xl),l=(k=d)==null?void 0:k.coldHashData,(m=Ks().resolve(new Es(Zp)))?g?e?n.yield(aq(m,g,e),2):n.yield(aq(m,g),2):n.F(2):n.return()):l?h?n.yield(bq(m,l,h),0):n.yield(bq(m,l),0):n.F(0)})}
function Ht(a,b){b=b===void 0?200:b;return a?b===300?st:qt:b===300?rt:pt}
function Ct(a){a=Object.keys(a);a=z(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,tr[b])return b}
function Dt(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var St=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",St);
function Tt(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||V());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=rs();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,St[b]=b in St?St[b]+1:0,a.sequence={index:St[b],groupKey:b},d.endOfSequence&&delete St[d.sequenceGroup]);(d.sendIsolatedPayload?Et:zt)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function po(a,b,c){c=c===void 0?{}:c;var d=$r;R("ytLoggingEventsDefaultDisabled",!1)&&$r===$r&&(d=null);Tt(a,b,d,c)}
;function Ut(a){return a.slice(0,void 0).map(function(b){return b.name}).join(" > ")}
;var Vt=new Set,Wt=0,Xt=0,Yt=0,Zt=[],$t=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function oo(a){au(a)}
function bu(a){au(a,"WARNING")}
function cu(a){a instanceof Error?au(a):(a=Qa(a)?JSON.stringify(a):String(a),a=new U(a),a.name="RejectedPromiseError",bu(a))}
function au(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(Wt>=5))){d=Zt;var k=Sb(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var p=0;p<a.args.length&&!(n=Xm(a.args[p],"params."+p,c,n),
n>=500);p++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(p in t){if(t[p]){var v="params."+p,x=Zm(t[p]);c[v]=x;n+=v.length+x.length;if(n>500)break}}else c.params=Zm(t)}if(d.length)for(p=0;p<d.length&&!(n=Xm(d[p],"params.context."+p,c,n),n>=500);p++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);p={message:e,name:f,lineNumber:m,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(p.lineNumber=
p.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Tm();c=z(a.Sa);for(d=c.next();!d.done;d=c.next())if(d=d.value,p.message&&p.message.match(d.xh)){a=d.weight;break a}a=z(a.Oa);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(p)){a=c.weight;break a}a=1}p.sampleWeight=a;a=z(Om);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.kc[p.name])for(e=z(c.kc[p.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=p.message.match(f.regexp)){p.params["params.error.original"]=d[0];e=f.groups;f={};
for(m=0;m<e.length;m++)f[e[m]]=d[m+1],p.params["params.error."+e[m]]=d[m+1];p.message=c.Fc(f);break}p.params||(p.params={});a=Tm();p.params["params.errorServiceSignature"]="msg="+a.Sa.length+"&cb="+a.Oa.length;p.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(p.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new Hg(Ig,"sample")).constructor!==Hg&&(p.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&
window.yterr(p);if(p.sampleWeight!==0&&!Vt.has(p.message)){if(g&&S("web_enable_error_204"))du(b===void 0?"ERROR":b,p);else{b=b===void 0?"ERROR":b;b==="ERROR"?(Um.jb("handleError",p),S("record_app_crashed_web")&&Yt===0&&p.sampleWeight===1&&(Yt++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:p.message}}}}),po("appCrashed",g)),Xt++):b==="WARNING"&&Um.jb("handleWarning",p);if(S("kevlar_gel_error_routing")){g=
b;h=h===void 0?{}:h;b:{a=z($t);for(c=a.next();!c.done;c=a.next())if(vo(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:p.stack};p.fileName&&(c.filename=p.fileName);a=p.lineNumber&&p.lineNumber.split?p.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:p.message,errorClassName:p.name,
sampleWeight:p.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));d=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Xl("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=z(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=p.params)for(e=z(Object.keys(d)),
f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(po("clientError",h),(g==="ERROR"||S("errors_flush_gel_always_killswitch"))&&Gt(void 0,void 0,!1))}S("suppress_error_204_logging")||du(b,p)}try{Vt.add(p.message)}catch(y){}Wt++}}}
function du(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=z(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=z(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Fm(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function eu(a){var b=B.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,qa(b))}
;function fu(){this.register=new Map}
function gu(a){a=z(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Ch("ABORTED")}
fu.prototype.clear=function(){gu(this);this.register.clear()};
var hu=new fu;var iu=Date.now().toString();
function ju(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(iu)for(a=1,b=0;b<iu.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^iu.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var ku,lu=C.ytLoggingDocDocumentNonce_;lu||(lu=ju(),D("ytLoggingDocDocumentNonce_",lu));ku=lu;function mu(a){this.h=a}
r=mu.prototype;r.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
r.getAsJspb=function(){var a=new Al;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&kf(a,2,we(this.h.veType)),this.h.veCounter!==void 0&&kf(a,6,we(this.h.veCounter)),this.h.elementIndex!==void 0&&kf(a,3,we(this.h.elementIndex)),this.h.isCounterfactual&&kf(a,5,se(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();xf(a,Al,7,b)}this.h.youtubeData!==void 0&&xf(a,zl,8,this.h.jspbYoutubeData);return a};
r.toString=function(){return JSON.stringify(this.getAsJson())};
r.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
r.getLoggingDirectives=function(){return this.h.loggingDirectives};function nu(a){return R("client-screen-nonce-store",{})[a===void 0?0:a]}
function ou(a,b){b=b===void 0?0:b;var c=R("client-screen-nonce-store");c||(c={},Wl("client-screen-nonce-store",c));c[b]=a}
function pu(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function qu(a){return R(pu(a===void 0?0:a))}
D("yt_logging_screen.getRootVeType",qu);function ru(){var a=R("csn-to-ctt-auth-info");a||(a={},Wl("csn-to-ctt-auth-info",a));return a}
function su(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function tu(a){a=nu(a===void 0?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",tu);function uu(a,b,c){var d=ru();(c=tu(c))&&delete d[c];b&&(d[a]=b)}
function vu(a){return ru()[a]}
D("yt_logging_screen.getCttAuthInfo",vu);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==nu(c)||b!==R(pu(c)))if(uu(a,d,c),ou(a,c),Wl(pu(c),b),b=function(){setTimeout(function(){a&&po("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:ku,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function wu(){var a=Dg(xu),b;return(new ri(function(c,d){a.onSuccess=function(e){rm(e)?c(new yu(e)):d(new zu("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new zu("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new zu("Request timed out","net.timeout",e))};
b=Fm("//googleads.g.doubleclick.net/pagead/id",a)})).uc(function(c){if(c instanceof yi){var d;
(d=b)==null||d.abort()}return wi(c)})}
function zu(a,b,c){$a.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(zu,$a);function yu(a){this.xhr=a}
;function Au(){this.h=0;this.i=null}
Au.prototype.then=function(a,b,c){return this.h===1&&a?(a=a.call(c,this.i))&&typeof a.then==="function"?a:Bu(a):this.h===2&&b?(a=b.call(c,this.i))&&typeof a.then==="function"?a:Cu(a):this};
Au.prototype.getValue=function(){return this.i};
Au.prototype.isRejected=function(){return this.h==2};
Au.prototype.$goog_Thenable=!0;function Cu(a){var b=new Au;a=a===void 0?null:a;b.h=2;b.i=a===void 0?null:a;return b}
function Bu(a){var b=new Au;a=a===void 0?null:a;b.h=1;b.i=a===void 0?null:a;return b}
;function Du(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:mm(a)?"same-origin":"cors",credentials:mm(a)?"same-origin":"include"};b={};for(var d=z(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Eu(){return mg()||(cd||dd)&&vo("applewebkit")&&!vo("version")&&(!vo("safari")||vo("gsa/"))||bd&&vo("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function Fu(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in El)if(El[d]==c.embeddedPlayerMode){b=El[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Gu(a){$a.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Hu;this.isTimeout=a instanceof zu&&a.errorCode=="net.timeout";this.isCanceled=a instanceof yi}
w(Gu,$a);Gu.prototype.name="BiscottiError";function Hu(){$a.call(this,"Biscotti ID is missing from server")}
w(Hu,$a);Hu.prototype.name="BiscottiMissingError";var xu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Iu=null;function Ju(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Eu())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if(Bg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Fu(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Pl(){var a=Ju();if(a!==void 0)return wi(a);Iu||(Iu=wu().then(Ku).uc(function(b){return Lu(2,b)}));
return Iu}
function Ku(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Hu;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Hu;a=a.id;Ql(a);Iu=Bu(a);Mu(18E5,2);return a}
function Lu(a,b){b=new Gu(b);Ql("");Iu=Cu(b);a>0&&Mu(12E4,a-1);throw b;}
function Mu(a,b){sm(function(){wu().then(Ku,function(c){return Lu(b,c)}).uc(pi)},a)}
function Nu(){try{var a=E("yt.ads.biscotti.getId_");return a?a():Pl()}catch(b){return wi(b)}}
;var yb=ra(["data-"]);function Ou(a){a&&(a.dataset?a.dataset[Pu()]="true":Ab(a))}
function Qu(a){return a?a.dataset?a.dataset[Pu()]:a.getAttribute("data-loaded"):null}
var Ru={};function Pu(){return Ru.loaded||(Ru.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Su(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||Dg(b);this.assets=a.assets||{};this.attrs=a.attrs||Dg(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Su.prototype.clone=function(){var a=new Su,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];Oa(c)=="object"?a[b]=Dg(c):a[b]=c}return a};var Tu=["share/get_share_panel"],Uu=["share/get_web_player_share_panel"],Vu=["feedback"],Wu=["notification/modify_channel_preference"],Xu=["browse/edit_playlist"],Yu=["subscription/subscribe"],Zu=["subscription/unsubscribe"];var $u=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",$u);function av(a){Rl($u,arguments)}
;function bv(a,b,c){cv(a,b,c===void 0?null:c)}
function dv(a){a=ev(a);var b=document.getElementById(a);b&&(As(a),b.parentNode.removeChild(b))}
function fv(a,b){a&&b&&(a=""+Ra(b),(a=gv[a])&&ys(a))}
function cv(a,b,c){c=c===void 0?null:c;var d=ev(a),e=document.getElementById(d),f=e&&Qu(e),g=e&&!f;f?b&&b():(b&&(f=ws(d,b),b=""+Ra(b),gv[b]=f),g||(e=hv(a,d,function(){Qu(e)||(Ou(e),zs(d),sm(function(){As(d)},0))},c)))}
function hv(a,b,c,d){d=d===void 0?null:d;var e=Kg("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Ib(e,vl(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ev(a){var b=document.createElement("a");wb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Wb(a)}
var gv={};function iv(a){var b=jv(a),c=document.getElementById(b),d=c&&Qu(c);d||c&&!d||(c=kv(a,b,function(){if(!Qu(c)){Ou(c);zs(b);var e=Xa(As,b);sm(e,0)}}))}
function kv(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=vl(a);Db(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function jv(a){var b=Kg("A");wb(b,new pb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Wb(a)}
;function lv(a){var b=B.apply(1,arguments);if(!mv(a)||b.some(function(d){return!mv(d)}))throw Error("Only objects may be merged.");
b=z(b);for(var c=b.next();!c.done;c=b.next())nv(a,c.value)}
function nv(a,b){for(var c in b)if(mv(b[c])){if(c in a&&!mv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});nv(a[c],b[c])}else if(ov(b[c])){if(c in a&&!ov(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);pv(a[c],b[c])}else a[c]=b[c];return a}
function pv(a,b){b=z(b);for(var c=b.next();!c.done;c=b.next())c=c.value,mv(c)?a.push(nv({},c)):ov(c)?a.push(pv([],c)):a.push(c);return a}
function mv(a){return typeof a==="object"&&!Array.isArray(a)}
function ov(a){return typeof a==="object"&&Array.isArray(a)}
;var qv="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function rv(a,b){var c=c===void 0?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=$b(window.location.href);e&&d.push(e);e=$b(a);if(Jb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),wb(d,a),a=d.href)if(a=ac(a),a=bc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:tu()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&sv(a,b,f)}else sv(a,b)}
function sv(a,b,c){a=tv(a);b=b?dc(b):"";c=c||5;Eu()&&fn(a,b,c)}
function tv(a){for(var b=z(qv),c=b.next();!c.done;c=b.next())a=jc(a,c.value);return"ST-"+Wb(a).toString(36)}
;function uv(a){jq.call(this,1,arguments);this.csn=a}
w(uv,jq);var sq=new kq("screen-created",uv),vv=[],wv=0,xv=new Map,yv=new Map,zv=new Map;
function Av(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Bv({cttAuthInfo:vu(b)||void 0},b),g=z(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(zg(k)||!k.trackingParams&&!k.veType)&&bu(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=Cv(h,b);if(k.veType&&!yv.has(l)&&!zv.has(l)&&!e){if(!S("il_attach_cache_limit")||xv.size<1E3){xv.set(l,[a,b,c,h]);return}S("il_attach_cache_limit")&&xv.size>1E3&&bu(new U("IL Attach cache exceeded limit"))}h=Cv(c,b);xv.has(h)?
Dv(c,b):zv.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Mb(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Ev("visualElementAttached",f,c):a?Tt("visualElementAttached",c,a,f):po("visualElementAttached",c,f)}
function Ev(a,b,c){vv.push({Ee:a,payload:c,th:void 0,options:b});wv||(wv=tq())}
function uq(a){if(vv){for(var b=z(vv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,po(c.Ee,c.payload,c.options));vv.length=0}wv=0}
function Cv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Dv(a,b){a=Cv(a,b);xv.has(a)&&(b=xv.get(a)||[],Av(b[0],b[1],b[2],[b[3]],!0),xv.delete(a))}
function Bv(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Fv(){try{return!!self.localStorage}catch(a){return!1}}
;function Gv(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Hv(a){if(Fv()){var b=Object.keys(window.localStorage);b=z(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Gv(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Iv(){if(!Fv())return!1;var a=yn(),b=Object.keys(window.localStorage);b=z(b);for(var c=b.next();!c.done;c=b.next())if(c=Gv(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Jv(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(R("INNERTUBE_CLIENT_NAME")==="WEB"||R("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Kv(a){if(R("LOGGED_IN",!0)&&Jv()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=$b(window.location.href);c&&b.push(c);c=$b(a);Jb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=ac(a),(b=bc(b))?(b=tv(b),b=(b=gn(b)||null)?im(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Jv()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&rv(a,b)}}
;function Lv(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&rv(a,b);if(c)return!1;Kv(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;a=ec(a,e);Kv(a);f=a+f;var h=h===void 0?tb:h;a:if(h=h===void 0?tb:h,f instanceof pb)h=f;else{for(a=0;a<h.length;++a)if(b=h[a],b instanceof rb&&b.ue(f)){h=new pb(f);break a}h=void 0}g=g.location;h=vb(h||qb);h!==void 0&&(g.href=h);return!0}
;function Mv(a){if(Bg(R("PLAYER_VARS",{}))!="1"){a&&Ol();try{Nu().then(function(){},function(){}),sm(Mv,18E5)}catch(b){am(b)}}}
;var Nv=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Ov(){var a=a===void 0?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;var b=Yb(Zb(5,a));if(S("enable_dark_theme_only_on_shorts")&&b!=null&&b.startsWith("/shorts/"))return"USER_INTERFACE_THEME_DARK";try{var c=jm(a).theme;return Nv.get(c)||null}catch(d){}return null}
;function Pv(){this.h={};if(this.i=jn()){var a=gn("CONSISTENCY");a&&Qv(this,{encryptedTokenJarContents:a})}}
Pv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Ma.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=z(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Qv(this,a)}};
function Qv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&fn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Rv=window.location.hostname.split(".").slice(-2).join(".");function Sv(){this.j=-1;var a=R("LOCATION_PLAYABILITY_TOKEN");R("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=Tv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Uv;function Vv(){Uv=E("yt.clientLocationService.instance");Uv||(Uv=new Sv,D("yt.clientLocationService.instance",Uv));return Uv}
r=Sv.prototype;
r.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
r.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,R("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=Tv(this))&&this.h.set("yt-location-playability-token",a,15552E3):fn("YT_CL",JSON.stringify({loctok:a}),15552E3,Rv,!0))};
function Tv(a){return a.h===void 0?new go("yt-client-location"):a.h}
r.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=Tv(this))&&this.h.remove("yt-location-playability-token"):hn("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
r.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;R("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
r.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
r.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function Wv(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);R("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=R("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;function Xv(){this.h={}}
Xv.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
Xv.prototype.get=function(a){if(this.contains(a))return this.h[a]};
Xv.prototype.set=function(a,b){this.h[a]=b};
Xv.prototype.remove=function(a){delete this.h[a]};function Yv(){this.mappings=new Xv}
Yv.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
Yv.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=Bb(b)}}return a};
new Yv;function Zv(a){return function(){return new a}}
;var $v={},aw=($v.WEB_UNPLUGGED="^unplugged/",$v.WEB_UNPLUGGED_ONBOARDING="^unplugged/",$v.WEB_UNPLUGGED_OPS="^unplugged/",$v.WEB_UNPLUGGED_PUBLIC="^unplugged/",$v.WEB_CREATOR="^creator/",$v.WEB_KIDS="^kids/",$v.WEB_EXPERIMENTS="^experiments/",$v.WEB_MUSIC="^music/",$v.WEB_REMIX="^music/",$v.WEB_MUSIC_EMBEDDED_PLAYER="^music/",$v.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",$v);
function bw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=aw[b];if(c){c=new RegExp(c);for(var d=z(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(aw).forEach(function(g){var h=z(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=z(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function cw(){}
cw.prototype.D=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?en:c;var d=a.clickTrackingParams,e=this.o,f=!1;f=f===void 0?!1:f;e=e===void 0?!1:e;var g=R("INNERTUBE_CONTEXT");if(g){g=Eg(g);S("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;h.clientName==="MWEB"&&h.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(h.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=
window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=k===void 0?!1:k;nn();var l="USER_INTERFACE_THEME_LIGHT";qn(165)?l="USER_INTERFACE_THEME_DARK":qn(174)?l="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");
k=k?l:Ov()||l;h.userInterfaceTheme=k;if(!f){if(k=vn())h.connectionType=k;S("web_log_effective_connection_type")&&(k=wn())&&(g.client.effectiveConnectionType=k)}var m;if(S("web_log_memory_total_kbytes")&&((m=C.navigator)==null?0:m.deviceMemory)){var n;m=(n=C.navigator)==null?void 0:n.deviceMemory;g.client.memoryTotalKbytes=""+m*1E6}S("web_gcf_hashes_innertube")&&(k=cq())&&(n=k.coldConfigData,m=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},n&&(g.client.configInfo.coldConfigData=
n),m&&(g.client.configInfo.coldHashData=m),k&&(g.client.configInfo.hotHashData=k));n=jm(C.location.href);!S("web_populate_internal_geo_killswitch")&&n.internalcountrycode&&(h.internalGeo=n.internalcountrycode);h.clientName==="MWEB"||h.clientName==="WEB"?(h.mainAppWebInfo={graftUrl:C.location.href},S("kevlar_woffle")&&$m.h&&(n=$m.h,h.mainAppWebInfo.pwaInstallabilityStatus=!n.h&&n.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=an(),
h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):h.clientName==="TVHTML5"&&(!S("web_lr_app_quality_killswitch")&&(n=R("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:n})),n=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:n}));if(!S("web_populate_time_zone_itc_killswitch")){b:{if(typeof Intl!=="undefined")try{var p=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(na){}p=
void 0}p&&(h.timeZone=p)}(p=R("EXPERIMENTS_TOKEN",""))?h.experimentsToken=p:delete h.experimentsToken;p=xm();Pv.h||(Pv.h=new Pv);h=Pv.h.h;n=[];m=0;for(var t in h)n[m++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:p,consistencyTokenJars:n});!S("web_prequest_context_killswitch")&&(t=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=t);p=nn();t=qn(58);p=p.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);p&&(g.user.lockedSafetyMode=
!0);S("warm_op_csn_cleanup")?e&&(f=tu())&&(g.clientScreenNonce=f):!f&&(f=tu())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Vv().setLocationOnInnerTubeContext(g);try{var v=nm(),x=v.bid;delete v.bid;g.adSignalsInfo={params:[],bid:x};var y=z(Object.entries(v));for(var G=y.next();!G.done;G=y.next()){var I=z(G.value),O=I.next().value,T=I.next().value;v=O;x=T;d=void 0;(d=g.adSignalsInfo.params)==null||d.push({key:v,value:""+
x})}var Ja,cb;if(((Ja=g.client)==null?void 0:Ja.clientName)==="TVHTML5"||((cb=g.client)==null?void 0:cb.clientName)==="TVHTML5_UNPLUGGED"&&S("add_ifa_to_tvh5_requests")){var ca=R("INNERTUBE_CONTEXT");ca.adSignalsInfo&&(g.adSignalsInfo.advertisingId=ca.adSignalsInfo.advertisingId,g.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",g.adSignalsInfo.limitAdTracking=ca.adSignalsInfo.limitAdTracking)}}catch(na){au(na)}y=g}else au(Error("Error: No InnerTubeContext shell provided in ytconfig.")),
y={};y={context:y};if(G=this.i(a)){this.h(y,G,b);var Z;b="/youtubei/v1/"+bw(this.j());(G=(Z=jt(a.commandMetadata,Cl))==null?void 0:Z.apiUrl)&&(b=G);Z=b;(b=R("INNERTUBE_HOST_OVERRIDE"))&&(Z=String(b)+String(ac(Z)));b={};S("json_condensed_response")&&(b.prettyPrint="false");Z=lm(Z,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:Z,eb:Du(Z),Ma:y,config:a};a.config.Vb?a.config.Vb.identity=c:a.config.Vb={identity:c};return a}au(new U("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(cw.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function dw(){}
w(dw,cw);function ew(){}
w(ew,dw);ew.prototype.D=function(){return{input:"/getDatasyncIdsEndpoint",eb:Du("/getDatasyncIdsEndpoint","GET"),Ma:{}}};
ew.prototype.j=function(){return[]};
ew.prototype.i=function(){};
ew.prototype.h=function(){};var fw={},gw=(fw.GET_DATASYNC_IDS=Zv(ew),fw);function hw(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function iw(){var a=hw();a.info||(a.info={});return a.info}
function jw(a){a=hw(a);a.metadata||(a.metadata={});return a.metadata}
function kw(a){a=hw(a);a.tick||(a.tick={});return a.tick}
function lw(a){a=hw(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function mw(a){a=lw(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function nw(a){var b=hw(a).nonce;b||(b=ju(),hw(a).nonce=b);return b}
;function ow(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function pw(a){a=a||"";var b=E("ytcsi.reference");b||(ow(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=ow(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var W={},qw=(W["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",W["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",W["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",W["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",W["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",W["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",W["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",W["asset.composition_policy"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",W["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",W["asset.history"]="LATENCY_ACTION_CREATOR_CMS_ASSET_HISTORY",W["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",W["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",W["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",W["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",W["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",W["asset.references"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",W["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",W["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",W["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",W["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",W["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",W["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",W["song.analytics"]=
"LATENCY_ACTION_CREATOR_SONG_ANALYTICS",W.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",W["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",W["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",W["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",W["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",W["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",W["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",W["channel.monetization"]=
"LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",W["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",W["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",W["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",W["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",W["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",W["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",W["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",
W["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",W["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",W.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",W["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",W["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",W["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",W["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",W["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",W["owner.bulk"]=
"LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",W["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",W["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",W["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",W["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",W["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",
W["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",W["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",W["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",W["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",W["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",W["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",W["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",W["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",W["playlist.videos"]=
"LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",W["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",W["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",W["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",W["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",W["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",W["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",W["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",W["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",
W["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",W["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",W["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",W["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",W["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",W["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",W["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",W["video.translations"]=
"LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",W),X={},rw=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X.app_startup="LATENCY_ACTION_APP_STARTUP",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X.direct_playback=
"LATENCY_ACTION_DIRECT_PLAYBACK",X.editor="LATENCY_ACTION_EDITOR",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",
X.management="LATENCY_ACTION_MANAGEMENT",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",
X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.projects="LATENCY_ACTION_PROJECTS",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",X.review="LATENCY_ACTION_REVIEW",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",
X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",
X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",
X);Object.assign(rw,qw);function sw(a,b){jq.call(this,1,arguments);this.timer=b}
w(sw,jq);var tw=new kq("aft-recorded",sw);D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var uw=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",uw);function vw(){this.h=0}
function ww(){vw.h||(vw.h=new vw);return vw.h}
vw.prototype.tick=function(a,b,c,d){xw(this,"tick_"+a+"_"+b)||po("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
vw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");xw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,po("latencyActionInfo",a,{cttAuthInfo:c}))};
vw.prototype.jspbInfo=function(){};
vw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");xw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,po("latencyActionSpan",a,{cttAuthInfo:c}))};
function xw(a,b){uw[b]=uw[b]||{count:0};var c=uw[b];c.count++;c.time=V();a.h||(a.h=An(function(){var d=V(),e;for(e in uw)uw[e]&&d-uw[e].time>6E4&&delete uw[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||bu(c)),!0):!1}
;var yw=window;function zw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Aw(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Bw(e.requestStart),e.responseEnd=Bw(e.responseEnd),e.redirectStart=Bw(e.redirectStart),e.redirectEnd=Bw(e.redirectEnd),e.domainLookupEnd=Bw(e.domainLookupEnd),e.connectStart=Bw(e.connectStart),e.connectEnd=
Bw(e.connectEnd),e.responseStart=Bw(e.responseStart),e.secureConnectionStart=Bw(e.secureConnectionStart),e.domainLookupStart=Bw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=S("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Bw(a){return Math.round(Cw()+a)}
function Cw(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=yw.performance||yw.mozPerformance||yw.msPerformance||yw.webkitPerformance||new zw;var Dw=!1,Ew=!1,Fw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Wa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||pi,Y);function Gw(a,b){if(!S("web_csi_action_sampling_enabled")||!hw(b).actionDisabled){var c=pw(b||"");lv(c.info,a);a.loadType&&(c=a.loadType,jw(b).loadType=c);lv(mw(b),a);c=nw(b);b=hw(b).cttAuthInfo;ww().info(a,c,b)}}
function Hw(){var a,b,c,d;return((d=Ks().resolve(new Es(Zp))==null?void 0:(a=$p())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Iw(a,b,c){if(!S("web_csi_action_sampling_enabled")||!hw(c).actionDisabled){var d=nw(c),e;if(e=S("web_csi_debug_sample_enabled")&&d){(Ks().resolve(new Es(Zp))==null?0:$p())&&!Ew&&(Ew=!0,Iw("gcfl",V(),c));var f,g,h;e=(Ks().resolve(new Es(Zp))==null?void 0:(f=$p())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Hw();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+
d.charCodeAt(g),g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;hw(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Gw(f,c));hw(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||S("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f=S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?f-Y.timeOrigin:f-(Y.timeOrigin||Y.timing.navigationStart);
try{Y.mark(e,{startTime:f})}catch(k){}}e=pw(c||"");e.tick[a]=b||V();if(e.callback&&e.callback[a])for(e=z(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=lw(c);e.gelTicks&&(e.gelTicks[a]=!0);f=kw(c);e=b||V();S("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=hw(c).cttAuthInfo;a==="_start"?(a=ww(),xw(a,"baseline_"+d)||po("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):ww().tick(a,d,b,f);Jw(c);return e}}}
function Kw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=bs+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Lw(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=z(Object.entries(R("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=z(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Mw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);Eb(window)&&a.setAttribute("nonce",Eb(window));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Cw(),Iw("rsf_"+b,c+Math.round(a.fetchStart)),Iw("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Nw(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Lb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Nb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Iw("wffs",Bw(b.startTime)),Iw("wffe",Bw(b.responseEnd)))}
function Ow(a){var b=Pw("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Pw(b[d],a);if(e)return e}return NaN}
function Pw(a,b){if(a=kw(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Jw(a){var b=Pw("_start",a),c=Ow(a),d=S("enable_cow_info_csi")||!Dw;b&&c&&d&&(pq(tw,new sw(Math.round(c-b),a)),Dw=!0)}
function Qw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Ob(a,function(c){return c.name==="first-paint"}))return Bw(a.startTime)}var b;
S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?b=Y.getEntriesByType("first-paint")[0].startTime:b=Y.timing.zh;return b?Math.max(0,b):0}
;function Rw(a,b){$l(function(){pw("").info.actionType=a;b&&Wl("TIMING_AFT_KEYS",b);Wl("TIMING_ACTION",a);var c=Lw();Object.keys(c).length>0&&Gw(c);c={isNavigation:!0,actionType:rw[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=R("PREVIOUS_ACTION");d&&(c.previousAction=rw[d]||"LATENCY_ACTION_UNKNOWN");if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=tu())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Kw();if(d===1||d===-1)c.isVisible=!0;jw();iw();
c.loadType="cold";d=iw();var e=Aw(),f=Cw(),g=R("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Iw("srt",e.responseStart),d.prerender!==1&&Iw("_start",f,void 0));d=Qw();d>0&&Iw("fpt",d);d=Aw();d.isPerformanceNavigationTiming&&Gw({performanceNavigationTiming:!0},void 0);Iw("nreqs",d.requestStart,void 0);Iw("nress",d.responseStart,void 0);Iw("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Iw("nrs",d.redirectStart,void 0),Iw("nre",
d.redirectEnd,void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Iw("ndnss",d.domainLookupStart,void 0),Iw("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Iw("ntcps",d.connectStart,void 0),Iw("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Cw()&&d.connectEnd-d.secureConnectionStart>0&&(Iw("nstcps",d.secureConnectionStart,void 0),Iw("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Nw();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Fw)Fw.hasOwnProperty(h)&&
(e=Fw[h],Mw(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=z(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Gw(c);c=lw();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=mw();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(jw().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=kw();e=lw();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Iw(k,Pw(k));else if(S("log_repeated_ytcsi_ticks"))for(f=
z(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Iw(k.slice(1),g);k={};d=!1;h=z(h);for(e=h.next();!e.done;e=h.next())d=e.value,lv(c,d),lv(k,d),d=!0;d&&Gw(k)}D("ytglobal.timingready_",!0);k=R("TIMING_ACTION");E("ytglobal.timingready_")&&k&&Sw()&&Ow()&&Jw()})()}
function Sw(){return $l(function(){return Tw()})()}
function Uw(a,b,c){$l(Gw)(a,b,c===void 0?!1:c)}
function Vw(a,b,c){return $l(Iw)(a,b,c)}
function Tw(){return $l(function(){return"_start"in kw()})()}
function Ww(){$l(function(){var a=nw();requestAnimationFrame(function(){setTimeout(function(){a===nw()&&Vw("ol",void 0,void 0)},0)})})()}
var Xw=window;Xw.ytcsi&&(Xw.ytcsi.infoGel=Uw,Xw.ytcsi.tick=Vw);var Yw="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),Zw=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function $w(a,b,c,d){this.D=a;this.ea=b;this.o=c;this.j=d;this.i=void 0;this.h=new Map;a.Pb||(a.Pb={});a.Pb=Object.assign({},gw,a.Pb)}
function ax(a,b,c,d){if($w.h!==void 0){if(d=$w.h,a=[a!==d.D,b!==d.ea,c!==d.o,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new U("InnerTubeTransportService is already initialized",a);
}else $w.h=new $w(a,b,c,d)}
function bx(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?en:c;var d=cx(a,b);return d?new ri(function(e,f){var g,h,k,l,m;return A(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.D(b,void 0,c);if(!h){f(new U("Error: Failed to build request for command.",b));n.F(0);break}Kv(h.input);l=((k=h.eb)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.o.hf){var p=h.config,t;p=p==null?void 0:(t=p.Vb)==null?void 0:t.sessionIndex;t=dn(0,{sessionIndex:p});m=Object.assign({},
Wv(l),t);n.F(4);break}return n.yield(dx(h.config,l),5);case 5:m=n.i;case 4:e(ex(a,h,m)),n.h=0}})}):wi(new U("Error: No request builder found for command.",b))}
function fx(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.j){d=z(Yw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function ex(a,b,c){var d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,p,t,v,x,y,G,I,O,T,Ja,cb,ca,Z,na,Na,Ma,Zg,$g,Nr,Or,Pr,Qr;return A(function(ia){switch(ia.h){case 1:ia.F(2);break;case 3:if((e=ia.i)&&!e.isExpired())return ia.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Ma)==null?0:g.context)){ia.F(4);break}h=b.Ma.context;ia.F(5);break;case 5:k=z([]),l=k.next();case 8:if(l.done){ia.F(4);break}m=l.value;return ia.yield(m.Bh(h),9);case 9:l=k.next();ia.F(8);break;case 4:if((n=a.i)==null||!n.Gh(b.input,b.Ma)){ia.F(12);break}return ia.yield(a.i.vh(b.input,
b.Ma),13);case 13:return p=ia.i,fx(a,p,b),ia.return(p);case 12:return(x=(v=b.config)==null?void 0:v.Eh)&&a.h.has(x)?t=a.h.get(x):(y=JSON.stringify(b.Ma),O=(I=(G=b.eb)==null?void 0:G.headers)!=null?I:{},b.eb=Object.assign({},b.eb,{headers:Object.assign({},O,c)}),T=Object.assign({},b.eb),b.eb.method==="POST"&&(T=Object.assign({},T,{body:y})),((Ja=b.config)==null?0:Ja.Je)&&Vw(b.config.Je),cb=function(){return a.ea.fetch(b.input,T,b.config)},t=cb(),x&&a.h.set(x,t)),ia.yield(t,14);
case 14:if((ca=ia.i)&&"error"in ca&&((Z=ca)==null?0:(na=Z.error)==null?0:na.details))for(Na=ca.error.details,Ma=z(Na),Zg=Ma.next();!Zg.done;Zg=Ma.next())$g=Zg.value,(Nr=$g["@type"])&&Zw.indexOf(Nr)>-1&&(delete $g["@type"],ca=$g);x&&a.h.has(x)&&a.h.delete(x);((Or=b.config)==null?0:Or.Ke)&&Vw(b.config.Ke);if(ca||(Pr=a.i)==null||!Pr.kh(b.input,b.Ma)){ia.F(15);break}return ia.yield(a.i.uh(b.input,b.Ma),16);case 16:ca=ia.i;case 15:return fx(a,ca,b),((Qr=b.config)==null?0:Qr.Ge)&&Vw(b.config.Ge),d(),ia.return(ca||
void 0)}})}
function cx(a,b){a:{a=a.D;var c,d=(c=jt(b,Dl))==null?void 0:c.signal;if(d&&a.Pb&&(c=a.Pb[d])){var e=c();break a}var f;if((c=(f=jt(b,Bl))==null?void 0:f.request)&&a.Td&&(f=a.Td[c])){e=f();break a}for(e in b)if(a.Wc[e]&&(b=a.Wc[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function dx(a,b){var c,d,e,f;return A(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Vb)==null?void 0:d.sessionIndex;var h=g.yield;var k=dn(0,{sessionIndex:e});if(!(k instanceof ri)){var l=new ri(pi);si(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Wv(b),f)))})}
;var gx=new Ds("INNERTUBE_TRANSPORT_TOKEN");function hx(){}
w(hx,dw);hx.prototype.j=function(){return Yu};
hx.prototype.i=function(a){return jt(a,Nl)||void 0};
hx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(hx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function ix(){}
w(ix,dw);ix.prototype.j=function(){return Zu};
ix.prototype.i=function(a){return jt(a,Ml)||void 0};
ix.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(ix.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var jx=new Ds("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function kx(a){this.u=a}
w(kx,dw);kx.prototype.j=function(){return Tu};
kx.prototype.i=function(a){return jt(a,Hl)||jt(a,Il)||jt(a,Gl)};
kx.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.u)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.u.i(b.clientParamIdentifier)}};
kx[Cs]=[jx];function lx(){}
w(lx,dw);lx.prototype.j=function(){return Vu};
lx.prototype.i=function(a){return jt(a,Fl)||void 0};
lx.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(lx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function mx(){}
w(mx,dw);mx.prototype.j=function(){return Wu};
mx.prototype.i=function(a){return jt(a,Ll)||void 0};
mx.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function nx(){}
w(nx,dw);nx.prototype.j=function(){return Xu};
nx.prototype.i=function(a){return jt(a,Kl)||void 0};
nx.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function ox(){}
w(ox,dw);ox.prototype.j=function(){return Uu};
ox.prototype.i=function(a){return jt(a,Jl)};
ox.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var px=new Ds("FETCH_FN_TOKEN"),qx=new Ds("PARSE_FN_TOKEN");function rx(a,b){var c=B.apply(2,arguments);a=a===void 0?0:a;U.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
w(rx,U);var sx=new Ds("NETWORK_SLI_TOKEN");function tx(a,b,c){this.h=a;this.i=b;this.j=c}
tx.prototype.fetch=function(a,b,c){var d=this,e,f,g;return A(function(h){e=ux(d,a,b);g=(f=d.i)!=null?f:fetch;return h.return(g(e).then(function(k){return d.handleResponse(k,c)}).catch(function(k){bu(k);
if((c==null?0:c.ae)&&k instanceof rx&&k.errorType===1)return Promise.reject(k)}))})};
function ux(a,b,c){if(a.h){var d=Yb(Zb(5,jc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;S("wug_networking_gzip_request")&&(a=Rq(c));return new window.Request(b,a)}
tx.prototype.handleResponse=function(a,b){var c,d=(c=this.j)!=null?c:JSON.parse;c=a.text().then(function(e){if((b==null?0:b.we)&&a.ok)return Tf(b.we,e);e=e.replace(")]}'","");if((b==null?0:b.ae)&&e)try{var f=d(e)}catch(h){throw new rx(1,"JSON parsing failed after fetch");}var g;return(g=f)!=null?g:d(e)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.ph(),c=c.then(function(e){bu(new U("Error: API fetch failed",a.status,a.url,e));return Object.assign({},e,{errorMetadata:{status:a.status}})}));
return c};
tx[Cs]=[new Es(sx),new Es(px),new Es(qx)];var vx=new Ds("NETWORK_MANAGER_TOKEN");var wx;function xx(){var a,b,c;return A(function(d){if(d.h==1)return a=Ks().resolve(gx),a?d.yield(bx(a),2):(bu(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return bu(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.mh;return d.return(c)}bu(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function yx(){var a;return(a=R("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var zx=C.caches,Ax;function Bx(a){var b=a.indexOf(":");return b===-1?{nd:a}:{nd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Cx(){return A(function(a){if(Ax!==void 0)return a.return(Ax);Ax=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return ya(d,2),d.yield(zx.open("test-only"),4);case 4:return d.yield(zx.delete("test-only"),5);case 5:d.h=3;d.o=0;break;case 2:if(c=za(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Ax)})}
function Dx(a){var b,c,d,e,f,g,h;A(function(k){if(k.h==1)return k.yield(Cx(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(zx.keys(),3)}c=k.i;d=z(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Bx(f),h=g.datasyncId,!h||a.includes(h)||b.push(zx.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function Ex(){var a,b,c,d,e,f,g;return A(function(h){if(h.h==1)return h.yield(Cx(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=yn("cache contains other");return h.yield(zx.keys(),3)}b=h.i;c=z(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Bx(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Fx(){try{return!!self.sessionStorage}catch(a){return!1}}
;function Gx(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Hx(a){if(Fx()){var b=Object.keys(window.sessionStorage);b=z(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Gx(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function Ix(){if(!Fx())return!1;var a=yn(),b=Object.keys(window.sessionStorage);b=z(b);for(var c=b.next();!c.done;c=b.next())if(c=Gx(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Jx(){xx().then(function(a){a&&(Ep(a),Dx(a),Hv(a),Hx(a))})}
function Kx(){var a=new Jr;Gj.pa(function(){var b,c,d,e,f;return A(function(g){switch(g.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){g.F(2);break}b=yn("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Ep(h);Dx(h);Hv(h);Hx(h);return g.return()}c=Iv();d=Ix();return g.yield(Ex(),3);case 3:return e=g.i,g.yield(Fp(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.wa()?Jx():a.h.add("publicytnetworkstatus-online",Jx,!0,void 0,void 0),g.h=0}})})}
;function Lx(){this.state=1;this.h=null}
r=Lx.prototype;r.initialize=function(a,b,c){if(a.program){var d,e=(d=a.interpreterUrl)!=null?d:null;if(a.interpreterSafeScript){var f=a.interpreterSafeScript;f?((f=f.privateDoNotAccessOrElseSafeScriptWrappedValue)?(d=gb(),f=new Fb(d?d.createScript(f):f)):f=null,d=f):d=null}else d=(f=a.interpreterScript)!=null?f:null;a.interpreterSafeUrl&&(e=ul(a.interpreterSafeUrl).toString());Mx(this,d,e,a.program,b,c)}else bu(Error("Cannot initialize botguard without program"))};
function Mx(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,bv(c,function(){window[g]?Nx(a,d,g,e):(a.state=3,dv(c),bu(new U("Unable to load Botguard","from "+c)))},f)):b?(f=Kg("SCRIPT"),b instanceof Fb?Hb(f,b):f.textContent=b,f.nonce=Eb(window),document.head.appendChild(f),document.head.removeChild(f),window[g]?Nx(a,d,g,e):(a.state=4,bu(new U("Unable to load Botguard from JS")))):bu(new U("Unable to load VM; no url or JS provided"))}
r.isLoading=function(){return this.state===2};
function Nx(a,b,c,d){a.state=5;try{var e=new sj({program:b,he:c,kd:{disable:!S("att_web_record_metrics"),ia:"aGIf"}});e.af.then(function(){a.state=6;d&&d(b)});
a.Nc(e)}catch(f){a.state=7,f instanceof Error&&bu(f)}}
r.invoke=function(a){a=a===void 0?{}:a;return this.Qc()?this.Cd({Xc:a}):null};
r.dispose=function(){this.Nc(null);this.state=8};
r.Qc=function(){return!!this.h};
r.Cd=function(a){return this.h.vd(a)};
r.Nc=function(a){pc(this.h);this.h=a};var Ox=[],Px=!1;function Qx(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&Eu()){var a=R("PLAYER_VARS",{});if(Bg(a)!="1"&&!Fu(a)){var b=function(){Px=!0;"google_ad_status"in window?Wl("DCLKSTAT",1):Wl("DCLKSTAT",2)};
try{bv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Ox.push(Gj.pa(function(){if(!(Px||"google_ad_status"in window)){try{fv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Px=!0;Wl("DCLKSTAT",3)}},5E3))}}}
function Rx(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Sx(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Tx(){Lx.apply(this,arguments)}
w(Tx,Lx);Tx.prototype.Nc=function(a){var b;(b=Sx())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.vd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
Tx.prototype.Qc=function(){return!!Sx()};
Tx.prototype.Cd=function(a){return Sx().bgvmc(a)};function Ux(a){Us.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.H},{from:"document_active",to:"document_disposed",action:this.D},{from:"document_disposed_preventable",to:"document_disposed",action:this.D},{from:"document_disposed_preventable",to:"flush_logs",action:this.u},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.u},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(Ux,Us);Ux.prototype.H=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Ux.prototype.D=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Ux.prototype.u=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
Ux.prototype.i=function(){this.h=new Map};function Vx(a){Us.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.u},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.D},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.u},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.u},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.D},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.D},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(Vx,Us);Vx.prototype.i=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Vx.prototype.h=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Vx.prototype.D=function(a,b){a(b==null?void 0:b.event)};
Vx.prototype.u=function(a,b){a(b==null?void 0:b.event)};function Wx(){this.o=new Ux;this.D=new Vx}
Wx.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.D.install(c)})};function Xx(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
Xx.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=tu(c===void 0?0:c)){a=this.client;d=new mu({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=Cv(d,c);yv.set(f,!0);Dv(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Bv({cttAuthInfo:vu(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Ev("visualElementGestured",f,d):a?Tt("visualElementGestured",d,a,f):po("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
Xx.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new mu({trackingParams:a}),b,c===void 0?0:c)};
Xx.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=tu(d);a||(a=(a=qu(d===void 0?0:d))?new mu({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Bv({cttAuthInfo:vu(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Ev("visualElementStateChanged",d,b):a?Tt("visualElementStateChanged",b,a,d):po("visualElementStateChanged",b,d))}};
function Yx(a,b){if(b===void 0)for(var c=su(),d=0;d<c.length;d++)c[d]!==void 0&&Yx(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Av(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Zx(){Wx.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));S("web_log_cfg_cee_ks")||An($x)}
w(Zx,Wx);Zx.prototype.j=function(){po("finalPayload",{csn:tu()})};
Zx.prototype.h=function(){gu(hu)};
Zx.prototype.i=function(){var a=Yx;Xx.h||(Xx.h=new Xx);a(Xx.h)};
function $x(){var a=R("CLIENT_EXPERIMENT_EVENTS");if(a){var b=Zd();a=z(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&po("genericClientExperimentEvent",{eventType:c});delete Vl.CLIENT_EXPERIMENT_EVENTS}}
;function ay(){}
function by(){var a=E("ytglobal.storage_");a||(a=new ay,D("ytglobal.storage_",a));return a}
ay.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(cy()):d.return()})};
function cy(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",ay);function no(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
no.prototype.Ea=function(a){this.handleError(a)};
no.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":dy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function dy(a,b){by().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:ey(c==null?void 0:c.usage),deviceStorageQuotaMbytes:ey(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function ey(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var fy={},gy=(fy["api.invalidparam"]=2,fy.auth=150,fy["drm.auth"]=150,fy["heartbeat.net"]=150,fy["heartbeat.servererror"]=150,fy["heartbeat.stop"]=150,fy["html5.unsupportedads"]=5,fy["fmt.noneavailable"]=5,fy["fmt.decode"]=5,fy["fmt.unplayable"]=5,fy["html5.missingapi"]=5,fy["html5.unsupportedlive"]=5,fy["drm.unavailable"]=5,fy["mrm.blocked"]=151,fy["embedder.identity.denied"]=152,fy);var hy=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function iy(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function jy(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=z(hy);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function ky(a,b,c,d){if(Qa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function ly(a){F.call(this);var b=this;this.api=a;this.Y=this.u=!1;this.B=[];this.R={};this.j=[];this.i=[];this.Z=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.U=S("web_player_split_event_bus_iframe");this.o=R("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.H=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.Y=!0;b.u=!1;b.sendMessage("initialDelivery",my(b));b.sendMessage("onReady");e=z(b.B);for(d=e.next();!d.done;d=e.next())ny(b,d.value);b.B=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.Z&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.R[e]||e==="onReady"||
(c=oy(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.U?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.R[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&iy(e)){var f=d;if(Qa(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=jy(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=jy(g);break;case "loadPlaylist":case "cuePlaylist":g=ky(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);iy(e)&&py(b,my(b))}}}};
qy.addEventListener("message",this.H);if(a=R("WIDGET_ID"))this.sessionId=a;ry(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.Z=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?gy[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
ry(this,"onVideoProgress",this.Ve.bind(this));ry(this,"onVolumeChange",this.We.bind(this));ry(this,"onApiChange",this.Oe.bind(this));ry(this,"onPlaybackQualityChange",this.Se.bind(this));ry(this,"onPlaybackRateChange",this.Te.bind(this));ry(this,"onStateChange",this.Ue.bind(this));ry(this,"onWebglSettingsChanged",this.Xe.bind(this));ry(this,"onCaptionsTrackListChanged",this.Pe.bind(this));ry(this,"captionssettingschanged",this.Qe.bind(this))}
w(ly,F);function py(a,b){a.sendMessage("infoDelivery",b)}
r=ly.prototype;r.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.Y?ny(this,a):this.B.push(a)};
function oy(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function ry(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function my(a){if(!a.api)return null;var b=a.api.getApiInterface();Pb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substring(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
r.Ue=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());py(this,a)};
r.Se=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());py(this,a)};
r.Te=function(a){py(this,{playbackRate:a})};
r.Oe=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
r.We=function(){py(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
r.Ve=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());py(this,a)};
r.Xe=function(){py(this,{sphericalProperties:this.api.getSphericalProperties()})};
r.Pe=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};py(this,a)}};
r.Qe=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};py(this,a)}};
function ny(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){bu(d)}}}
r.aa=function(){F.prototype.aa.call(this);qy.removeEventListener("message",this.H);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.U?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var qy=window;function sy(a,b,c){F.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=S("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.da){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=ty(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=uy(g,f))&&vy(d,g,f))}}}}}};
wy.addEventListener("message",this.i);vy(this,"RECEIVING")}
w(sy,F);r=sy.prototype;r.addListener=function(a,b){if(!(a in this.h)){var c=this.Re.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
r.Re=function(a,b){this.da||vy(this,a,xy(a,b))};
r.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
r.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
r.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function ty(a,b){switch(a){case "loadVideoById":return[jy(b)];case "cueVideoById":return[jy(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[ky(b)];case "cuePlaylist":return[ky(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function uy(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function xy(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function vy(a,b,c){a.da||(b={id:a.id,command:b},c&&(b.data=c),yy.postMessage(JSON.stringify(b),a.origin))}
r.aa=function(){wy.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);F.prototype.aa.call(this)};
var wy=window,yy=window.parent;var zy=new Tx;function Ay(){return zy.Qc()}
function By(a){a=a===void 0?{}:a;return zy.invoke(a)}
;function Cy(a,b,c,d,e){F.call(this);var f=this;this.B=b;this.webPlayerContextConfig=d;this.vc=e;this.Ab=!1;this.api={};this.ja=this.u=null;this.U=new M;this.h={};this.Z=this.ta=this.elementId=this.Bb=this.config=null;this.Y=!1;this.j=this.H=null;this.Va={};this.wc=["onReady"];this.lastError=null;this.Tb=NaN;this.R={};this.ga=0;this.i=this.o=a;rc(this,this.U);Dy(this);c?this.ga=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(Ey(this),Fy(this))}
w(Cy,F);r=Cy.prototype;r.getId=function(){return this.B};
r.loadNewVideoConfig=function(a){if(!this.da){this.ga&&(clearTimeout(this.ga),this.ga=0);var b=a||{};b instanceof Su||(b=new Su(b));this.config=b;this.setConfig(a);Fy(this);this.isReady()&&Gy(this)}};
function Ey(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.B,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.B:a.config.attrs.id=a.B);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
r.setConfig=function(a){this.Bb=a;this.config=Hy(a);Ey(this);if(!this.ta){var b;this.ta=Iy(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Aj(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Aj(Number(a)||a))};
function Gy(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Jy(a){var b=!0,c=Ky(a);c&&a.config&&(b=c.dataset.version===Ly(a));return b&&!!E("yt.player.Application.create")}
function Fy(a){if(!a.da&&!a.Y){var b=Jy(a);if(b&&(Ky(a)?"html5":null)==="html5")a.Z="html5",a.isReady()||My(a);else if(Ny(a),a.Z="html5",b&&a.j&&a.o)a.o.appendChild(a.j),My(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Oy(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?Hy(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.vc);My(a)};
a.Y=!0;b?a.H():(bv(Ly(a),a.H),(b=Py(a))&&iv(b||""),Qy(a)&&!c&&D("yt.player.Application.create",null))}}}
function Ky(a){var b=Jg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function My(a){if(!a.da){var b=Ky(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Y=!1;if(!Oy(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}Ry(a)}else a.Tb=setTimeout(function(){My(a)},50)}}
function Ry(a){Dy(a);a.Ab=!0;var b=Ky(a);if(b){a.u=Sy(a,b,"addEventListener");a.ja=Sy(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Sy(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);Gy(a);a.ta&&a.ta(a.api);a.U.jb("onReady",a.api)}
function Sy(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new U("PlayerProxy error in method call",{error:f,method:c,playerId:a.B}),e.level="WARNING",e;}}}
function Dy(a){a.Ab=!1;if(a.ja)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ja(b,a.h[b]);for(var c in a.R)a.R.hasOwnProperty(c)&&clearTimeout(Number(c));a.R={};a.u=null;a.ja=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Bb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
r.isReady=function(){return this.Ab};
r.addEventListener=function(a,b){var c=this,d=Iy(this,b);d&&(Jb(this.wc,a)>=0||this.h[a]||(b=Ty(this,a),this.u&&this.u(a,b)),this.U.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
r.removeEventListener=function(a,b){this.da||(b=Iy(this,b))&&this.U.unsubscribe(a,b)};
function Iy(a,b){var c=b;if(typeof b==="string"){if(a.Va[b])return a.Va[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){throw d=new U("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Va[b]=c}return c?c:null}
function Ty(a,b){function c(d){function e(){if(!a.da)try{a.U.jb(b,d!=null?d:void 0)}catch(h){var g=new U("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.B,data:d,originalStack:h.stack,componentStack:h.Sd});g.level="WARNING";throw g;}}
if(Oy(a,"web_player_publish_events_immediately"))e();else{var f=setTimeout(function(){e();var g=a.R,h=String(f);h in g&&delete g[h]},0);
Ag(a.R,String(f))}}
return a.h[b]=c}
r.getPlayerType=function(){return this.Z||(Ky(this)?"html5":null)};
r.getLastError=function(){return this.lastError};
function Ny(a){a.cancel();Dy(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=Ky(a);b&&(Jy(a)||!Qy(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
r.cancel=function(){this.H&&fv(Ly(this),this.H);clearTimeout(this.Tb);this.Y=!1};
r.aa=function(){Ny(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new U("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Va=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Bb=this.config=this.api=null;delete this.o;delete this.i;F.prototype.aa.call(this)};
function Qy(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function Ly(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Py(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Oy(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function Hy(a){for(var b={},c=z(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?Dg(e):e}return b}
;var Uy={},Vy="player_uid_"+(Math.random()*1E9>>>0);function Wy(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?Jg(c):c;var e=Vy+"_"+Ra(c),f=Uy[e];if(f&&d)return Xy(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Cy(c,e,a,b,void 0);Uy[e]=f;f.addOnDisposeCallback(function(){delete Uy[f.getId()]});
return f.api}
function Xy(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Yy=null,Zy=null;
function $y(){Ww();var a=nn(),b=qn(119),c=window.devicePixelRatio>1;if(document.body&&Oj(document.body,"exp-invert-logo"))if(c&&!Oj(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Oj(d,"inverted-hdpi")){var e=Mj(d);Nj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Oj(document.body,"inverted-hdpi")&&Pj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=rn(b)||0;d=c?d|67108864:d&-67108865;d===0?delete kn[b]:(c=d.toString(16),kn[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in kn)kn.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(kn[f])));var f=d.join("&");fn(b,f,63072E3,a.i,c)}}
function az(){bz()}
function cz(){Vw("ep_init_pr");bz()}
function bz(){var a=Yy.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function dz(){Yy&&Yy.sendAbandonmentPing&&Yy.sendAbandonmentPing();R("PL_ATT")&&zy.dispose();for(var a=Gj,b=0,c=Ox.length;b<c;b++)a.qa(Ox[b]);Ox.length=0;dv("//static.doubleclick.net/instream/ad_status.js");Px=!1;Wl("DCLKSTAT",0);qc(Zy);Yy&&(Yy.removeEventListener("onVideoDataChange",az),Yy.destroy())}
;D("yt.setConfig",Wl);D("yt.config.set",Wl);D("yt.setMsg",av);D("yt.msgs.set",av);D("yt.logging.errors.log",au);
D("writeEmbed",function(){var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}Mv(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Rw("embed",["ol"]);c=yx();if(!c.serializedForcedExperimentIds){var d=jm(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)&&Rw("watch",["pbs","pbu","pbp"]);Yy=Wy(a,c);Yy.addEventListener("onVideoDataChange",az);Yy.addEventListener("onReady",cz);a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?Zy=new ly(Yy):R("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Zy=new sy(Yy,a,b));Qx();S("ytidb_create_logger_embed_killswitch")||mo();a={};Zx.h||(Zx.h=new Zx);Zx.h.install((a.flush_logs={callback:function(){Gt()}},a));
Zr();S("ytidb_clear_embedded_player")&&Gj.pa(function(){var f,g;if(!wx){var h=Ks();Gs(h,{pc:vx,zd:tx});var k={Wc:{feedbackEndpoint:Zv(lx),modifyChannelNotificationPreferenceEndpoint:Zv(mx),playlistEditEndpoint:Zv(nx),shareEntityEndpoint:Zv(kx),subscribeEndpoint:Zv(hx),unsubscribeEndpoint:Zv(ix),webPlayerShareEntityServiceEndpoint:Zv(ox)}},l=Vv(),m={};l&&(m.client_location=l);f===void 0&&(f=cn());g===void 0&&(g=h.resolve(vx));ax(k,g,f,m);Gs(h,{pc:gx,Ad:$w.h});wx=h.resolve(gx)}Kx()})});
D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||Ay);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||By);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||Rx);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Lv);D("yt.util.activity.init",E("yt.util.activity.init")||ns);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||rs);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||ps);window.addEventListener("load",$l(function(){$y()}));
window.addEventListener("pageshow",$l(function(a){a.persisted||$y()}));
window.addEventListener("pagehide",$l(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?dz():a.persisted||dz()}));
window.onerror=function(a,b,c,d,e){var f;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var g=!1,h=Xl("log_window_onerror_fraction");if(h&&Math.random()<h)g=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){g=!0;break}}if(g){g=!1;e?g=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(g=!0,h=a.message,b=a.filename,c=a.lineno,d=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new U(h),e.name="UnhandledWindowError",e.message=
h,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d);if(!S("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=f)==null||!m.componentStack)if(m=a.Sd)f||(f={}),f.componentStack=Ut(m)}f&&eu(e,f);g?au(e):bu(e)}};
Hi=cu;window.addEventListener("unhandledrejection",function(a){cu(a.reason)});
Kb(R("ERRORS")||[],function(a){au.apply(null,a)});
Wl("ERRORS",[]);}).call(this);
