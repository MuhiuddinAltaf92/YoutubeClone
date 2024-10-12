(function(){'use strict';var p;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ca(this);function w(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
w("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
w("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ia(aa(this))}})}return a});
function ia(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ja(a){return a.raw=a}
function ka(a,b){a.raw=b;return a}
function x(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function la(a){if(!(a instanceof Array)){a=x(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ma(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var oa=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ma(d,e)&&(a[e]=d[e])}return a};
w("Object.assign",function(a){return a||oa});
var pa=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},qa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=pa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ra;
if(typeof Object.setPrototypeOf=="function")ra=Object.setPrototypeOf;else{var sa;a:{var ua={a:!0},va={};try{va.__proto__=ua;sa=va.a;break a}catch(a){}sa=!1}ra=sa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var wa=ra;
function y(a,b){a.prototype=pa(b.prototype);a.prototype.constructor=a;if(wa)wa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Ba=b.prototype}
function xa(){this.A=!1;this.m=null;this.i=void 0;this.h=1;this.v=this.l=0;this.P=this.j=null}
function ya(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
xa.prototype.H=function(a){this.i=a};
function za(a,b){a.j={exception:b,dd:!0};a.h=a.l||a.v}
xa.prototype.return=function(a){this.j={return:a};this.h=this.v};
xa.prototype.yield=function(a,b){this.h=b;return{value:a}};
xa.prototype.B=function(a){this.h=a};
function Aa(a,b,c){a.l=b;c!=void 0&&(a.v=c)}
function Ba(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Ca(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.dd?a.h=a.l||a.v:b.B!=void 0&&a.v<b.B?(a.h=b.B,a.j=null):a.h=a.v:a.h=0}
function Da(a){this.h=new xa;this.i=a}
function Ea(a,b){ya(a.h);var c=a.h.m;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ga(a)}
function Fa(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.m=null,za(a.h,g),Ga(a)}a.h.m=null;d.call(a.h,f);return Ga(a)}
function Ga(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,za(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.dd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ha(a){this.next=function(b){ya(a.h);a.h.m?b=Fa(a,a.h.m.next,b,a.h.H):(a.h.H(b),b=Ga(a));return b};
this.throw=function(b){ya(a.h);a.h.m?b=Fa(a,a.h.m["throw"],b,a.h.H):(za(a.h,b),b=Ga(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ia(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ia(new Ha(new Da(a)))}
function B(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
w("Reflect",function(a){return a?a:{}});
w("Reflect.construct",function(){return qa});
w("Reflect.setPrototypeOf",function(a){return a?a:wa?function(b,c){try{return wa(b,c),!0}catch(d){return!1}}:null});
w("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.A=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.v()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.v=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.da),reject:g(this.v)}};
b.prototype.da=function(g){if(g===this)this.v(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ia(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.ba(g):this.m(g)}};
b.prototype.ba=function(g){var h=void 0;try{h=g.then}catch(k){this.v(k);return}typeof h=="function"?this.xa(h,g):this.m(g)};
b.prototype.v=function(g){this.H(2,g)};
b.prototype.m=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(this.h!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;this.h===2&&this.ga();this.P()};
b.prototype.ga=function(){var g=this;e(function(){if(g.W()){var h=fa.console;typeof h!=="undefined"&&h.error(g.j)}},1)};
b.prototype.W=function(){if(this.A)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.P=function(){if(this.i!=null){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ia=function(g){var h=this.l();g.Yb(h.resolve,h.reject)};
b.prototype.xa=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,t){return typeof r=="function"?function(v){try{l(r(v))}catch(u){n(u)}}:t}
var l,n,m=new b(function(r,t){l=r;n=t});
this.Yb(k(g,l),k(h,n));return m};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Yb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;this.i==null?f.i(k):this.i.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=x(g),n=l.next();!n.done;n=l.next())d(n.value).Yb(h,k)})};
b.all=function(g){var h=x(g),k=h.next();return k.done?d([]):new b(function(l,n){function m(v){return function(u){r[v]=u;t--;t==0&&l(r)}}
var r=[],t=0;do r.push(void 0),t++,d(k.value).Yb(m(r.length-1),n),k=h.next();while(!k.done)})};
return b});
w("Object.setPrototypeOf",function(a){return a||wa});
w("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
w("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=x(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ma(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(n.get(k)!=2||n.get(l)!=3)return!1;n.delete(k);n.set(l,4);return!n.has(k)&&n.get(l)==4}catch(m){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ma(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ma(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ma(k,g)&&ma(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ma(k,g)&&ma(k[g],this.h)?delete k[g][this.h]:!1};
return b});
w("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ia(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h[0][l];if(n&&ma(h[0],l))for(h=0;h<n.length;h++){var m=n[h];if(k!==k&&m.key!==m.key||k===m.key)return{id:l,list:n,index:h,entry:m}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=x(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(x([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||n.value[1]!="s")return!1;n=l.next();return n.done||n.value[0].x!=4||n.value[1]!="t"||!l.next().done?!1:!0}catch(m){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ja(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
w("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
function Ma(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
w("Array.prototype.entries",function(a){return a?a:function(){return Ma(this,function(b,c){return[b,c]})}});
w("Array.prototype.keys",function(a){return a?a:function(){return Ma(this,function(b){return b})}});
w("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
w("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
w("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
w("Set",function(a){function b(c){this.h=new Map;if(c){c=x(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(x([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
w("Array.prototype.values",function(a){return a?a:function(){return Ma(this,function(b,c){return c})}});
w("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
w("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
w("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
w("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
w("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ma(b,d)&&c.push(b[d]);return c}});
w("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
w("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
w("String.prototype.includes",function(a){return a?a:function(b,c){return Ja(this,b,"includes").indexOf(b,c||0)!==-1}});
w("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
w("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
w("Math.clz32",function(a){return a?a:function(b){b=Number(b)>>>0;if(b===0)return 32;var c=0;(b&4294901760)===0&&(b<<=16,c+=16);(b&4278190080)===0&&(b<<=8,c+=8);(b&4026531840)===0&&(b<<=4,c+=4);(b&3221225472)===0&&(b<<=2,c+=2);(b&2147483648)===0&&c++;return c}});
w("Math.log10",function(a){return a?a:function(b){return Math.log(b)/Math.LN10}});
w("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ma(b,d)&&c.push([d,b[d]]);return c}});
w("globalThis",function(a){return a||fa});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Na=Na||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||typeof c.execScript=="undefined"||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Oa(a,b){var c=E("CLOSURE_FLAGS");a=c&&c[a];return a!=null?a:b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function Pa(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=Pa(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Ra(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(Math.random()*1E9>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Xa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Va:Wa;return Xa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(){return Date.now()}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.Ba=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function ab(a){return a}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
$a(bb,Error);bb.prototype.name="CustomError";function cb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;var db=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};var eb;function fb(){if(eb===void 0){var a=null,b=C.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:ab,createScript:ab,createScriptURL:ab})}catch(c){C.console&&C.console.error(c.message)}eb=a}else eb=a}return eb}
;function gb(a,b){this.h=a===hb&&b||""}
gb.prototype.toString=function(){return this.h};
function ib(a){return new gb(hb,a)}
var hb={};ib("");function jb(a){this.h=a}
jb.prototype.toString=function(){return this.h+""};
function kb(a){if(a instanceof jb&&a.constructor===jb)return a.h;Pa(a);return"type_error:TrustedResourceUrl"}
var lb={};function mb(a){var b=fb();a=b?b.createScriptURL(a):a;return new jb(a,lb)}
;/*

 SPDX-License-Identifier: Apache-2.0
*/
var nb=ja([""]),ob=ka(["\x00"],["\\0"]),pb=ka(["\n"],["\\n"]),qb=ka(["\x00"],["\\u0000"]);function rb(a){return a.toString().indexOf("`")===-1}
rb(function(a){return a(nb)})||rb(function(a){return a(ob)})||rb(function(a){return a(pb)})||rb(function(a){return a(qb)});function sb(a){this.h=a}
sb.prototype.toString=function(){return this.h};
var tb=new sb("about:invalid#zClosurez");function ub(a){this.le=a}
function vb(a){return new ub(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var wb=[vb("data"),vb("http"),vb("https"),vb("mailto"),vb("ftp"),new ub(function(a){return/^[^:]*([/?#]|$)/.test(a)})],xb=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function yb(a){if(a instanceof sb)if(a instanceof sb)a=a.h;else throw Error("");else a=xb.test(a)?a:void 0;return a}
;function zb(a,b){b=yb(b);b!==void 0&&(a.href=b)}
;function Ab(){this.h=Bb[0].toLowerCase()}
Ab.prototype.toString=function(){return this.h};var Cb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Db=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=typeof a==="string"?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Eb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Fb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Gb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Db(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Hb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Ib(a,b){b=Cb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Jb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Kb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function Lb(a){var b=Mb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function Nb(a){for(var b in a)return!1;return!0}
function Ob(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Pb(a){return a!==null&&"privembed"in a?a.privembed:!1}
function Qb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Rb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function Sb(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Sb(a[c]);return b}
var Tb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Ub(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Tb.length;f++)c=Tb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function Vb(a){this.h=a}
Vb.prototype.toString=function(){return this.h.toString()};function Wb(a){var b="true".toString(),c=[new Ab];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Ab)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Xb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;var Yb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Zb(a,b){if(b instanceof jb)a.href=kb(b).toString(),a.rel="stylesheet";else{if(Yb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=yb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;function $b(a){var b,c;return(a=(c=(b=a.document).querySelector)==null?void 0:c.call(b,"script[nonce]"))?a.nonce||a.getAttribute("nonce")||"":""}
;function ac(a){this.h=a}
ac.prototype.toString=function(){return this.h.toString()};function bc(a){var b=$b(a.ownerDocument&&a.ownerDocument.defaultView||window);b&&a.setAttribute("nonce",b)}
function cc(a,b){if(b instanceof ac)b=b.h;else throw Error("");a.textContent=b;bc(a)}
function dc(a,b){a.src=kb(b);bc(a)}
;function ec(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function fc(a){var b=E("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=hc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,ic[c])c=ic[c];else{c=String(c);if(!ic[c]){var f=/function\s+([^\(]+)/m.exec(c);ic[c]=f?f[1]:"[Anonymous]"}c=ic[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function hc(a,b){b||(b={});b[jc(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[jc(a)]&&(c+="\nCaused by: ",a.stack&&a.stack.indexOf(a.toString())==0||(c+=typeof a==="string"?a:a.message+"\n"),c+=hc(a,b));return c}
function jc(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var ic={};function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function sc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function tc(a,b){b=sc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function uc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var vc=/#|$/,wc=/[?&]($|#)/;function xc(a,b){for(var c=a.search(vc),d=0,e,f=[];(e=uc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(wc,"$1")}
;function yc(a){this.h=a}
;function zc(a,b,c){this.l=a;this.j=b;this.fields=c||[];this.h=new Map}
p=zc.prototype;p.Hd=function(a){var b=B.apply(1,arguments),c=this.vc(b);c?c.push(new yc(a)):this.td(a,b)};
p.td=function(a){var b=this.Oc(B.apply(1,arguments));this.h.set(b,[new yc(a)])};
p.vc=function(){var a=this.Oc(B.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
p.Yd=function(){var a=this.vc(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
p.clear=function(){this.h.clear()};
p.Oc=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function Ac(a,b){zc.call(this,a,3,b)}
y(Ac,zc);Ac.prototype.i=function(a){var b=B.apply(1,arguments),c=0,d=this.Yd(b);d&&(c=d.h);this.td(c+a,b)};function Bc(a,b){zc.call(this,a,2,b)}
y(Bc,zc);Bc.prototype.record=function(a){this.Hd(a,B.apply(1,arguments))};function Cc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function Dc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?Dc.apply(null,d):Cc(d)}}
;function G(){this.V=this.V;this.v=this.v}
G.prototype.V=!1;G.prototype.dispose=function(){this.V||(this.V=!0,this.U())};
G.prototype[Symbol.dispose]=function(){this.dispose()};
function Ec(a,b){a.addOnDisposeCallback(Ya(Cc,b))}
G.prototype.addOnDisposeCallback=function(a,b){this.V?b!==void 0?a.call(b):a():(this.v||(this.v=[]),this.v.push(b!==void 0?Xa(a,b):a))};
G.prototype.U=function(){if(this.v)for(;this.v.length;)this.v.shift()()};function Fc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Fc.prototype.stopPropagation=function(){this.j=!0};
Fc.prototype.preventDefault=function(){this.defaultPrevented=!0};var Gc=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();var Hc=Oa(1,!0),Ic=Oa(610401301,!1),Jc=Oa(188588736,Hc),Kc=Oa(645172343,Hc);function Lc(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Mc,Nc=C.navigator;Mc=Nc?Nc.userAgentData||null:null;function Oc(a){return Ic?Mc?Mc.brands.some(function(b){return(b=b.brand)&&b.indexOf(a)!=-1}):!1:!1}
function H(a){return Lc().indexOf(a)!=-1}
;function Pc(){return Ic?!!Mc&&Mc.brands.length>0:!1}
function Qc(){return Pc()?!1:H("Opera")}
function Rc(){return H("Firefox")||H("FxiOS")}
function Sc(){return Pc()?Oc("Chromium"):(H("Chrome")||H("CriOS"))&&!(Pc()?0:H("Edge"))||H("Silk")}
;function Tc(){return Ic?!!Mc&&!!Mc.platform:!1}
function Uc(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function Vc(a){Vc[" "](a);return a}
Vc[" "]=function(){};var Wc=Qc(),Xc=Pc()?!1:H("Trident")||H("MSIE"),Yc=H("Edge"),Zc=H("Gecko")&&!(Lc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),$c=Lc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge");$c&&H("Mobile");Tc()||H("Macintosh");Tc()||H("Windows");(Tc()?Mc.platform==="Linux":H("Linux"))||Tc()||H("CrOS");var ad=Tc()?Mc.platform==="Android":H("Android");Uc();H("iPad");H("iPod");Uc()||H("iPad")||H("iPod");Lc().toLowerCase().indexOf("kaios");function bd(a,b){Fc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a(bd,Fc);var cd={2:"touch",3:"pen",4:"mouse"};
bd.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Zc){a:{try{Vc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=typeof a.pointerType==="string"?a.pointerType:cd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&bd.Ba.preventDefault.call(this)};
bd.prototype.stopPropagation=function(){bd.Ba.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
bd.prototype.preventDefault=function(){bd.Ba.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var dd="closure_listenable_"+(Math.random()*1E6|0);var ed=0;function fd(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ec=e;this.key=++ed;this.Pb=this.Xb=!1}
function gd(a){a.Pb=!0;a.listener=null;a.proxy=null;a.src=null;a.ec=null}
;function hd(a){this.src=a;this.listeners={};this.h=0}
hd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=id(a,b,d,e);g>-1?(b=a[g],c||(b.Xb=!1)):(b=new fd(b,this.src,f,!!d,e),b.Xb=c,a.push(b));return b};
hd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=id(e,b,c,d);return b>-1?(gd(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function jd(a,b){var c=b.type;c in a.listeners&&Ib(a.listeners[c],b)&&(gd(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function id(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Pb&&f.listener==b&&f.capture==!!c&&f.ec==d)return e}return-1}
;var kd="closure_lm_"+(Math.random()*1E6|0),ld={},md=0;function nd(a,b,c,d,e){if(d&&d.once)od(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)nd(a,b[f],c,d,e);else c=pd(c),a&&a[dd]?a.listen(b,c,Ra(d)?!!d.capture:!!d,e):qd(a,b,c,!1,d,e)}
function qd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=rd(a);h||(a[kd]=h=new hd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=sd();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Gc||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(td(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");md++}}
function sd(){function a(c){return b.call(a.src,a.listener,c)}
var b=ud;return a}
function od(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)od(a,b[f],c,d,e);else c=pd(c),a&&a[dd]?a.h.add(String(b),c,!0,Ra(d)?!!d.capture:!!d,e):qd(a,b,c,!0,d,e)}
function vd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)vd(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=pd(c),a&&a[dd])?a.h.remove(String(b),c,d,e):a&&(a=rd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=id(b,c,d,e)),(c=a>-1?b[a]:null)&&wd(c))}
function wd(a){if(typeof a!=="number"&&a&&!a.Pb){var b=a.src;if(b&&b[dd])jd(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(td(c),d):b.addListener&&b.removeListener&&b.removeListener(d);md--;(c=rd(b))?(jd(c,a),c.h==0&&(c.src=null,b[kd]=null)):gd(a)}}}
function td(a){return a in ld?ld[a]:ld[a]="on"+a}
function ud(a,b){if(a.Pb)a=!0;else{b=new bd(b,this);var c=a.listener,d=a.ec||a.src;a.Xb&&wd(a);a=c.call(d,b)}return a}
function rd(a){a=a[kd];return a instanceof hd?a:null}
var xd="__closure_events_fn_"+(Math.random()*1E9>>>0);function pd(a){if(typeof a==="function")return a;a[xd]||(a[xd]=function(b){return a.handleEvent(b)});
return a[xd]}
;function yd(){G.call(this);this.h=new hd(this);this.Za=this;this.ga=null}
$a(yd,G);yd.prototype[dd]=!0;p=yd.prototype;p.addEventListener=function(a,b,c,d){nd(this,a,b,c,d)};
p.removeEventListener=function(a,b,c,d){vd(this,a,b,c,d)};
function zd(a,b){var c=a.ga;if(c){var d=[];for(var e=1;c;c=c.ga)d.push(c),++e}a=a.Za;c=b.type||b;typeof b==="string"?b=new Fc(b,a):b instanceof Fc?b.target=b.target||a:(e=b,b=new Fc(c,a),Ub(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=Ad(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Ad(g,c,!0,b)&&e,b.j||(e=Ad(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Ad(g,c,!1,b)&&e}
p.U=function(){yd.Ba.U.call(this);this.removeAllListeners();this.ga=null};
p.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
p.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,gd(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function Ad(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Pb&&g.capture==c){var h=g.listener,k=g.ec||g.src;g.Xb&&jd(a.h,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;function Bd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Bd.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Cd(a,b){a.l(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function Dd(){}
function Ed(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Fd(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
p=Fd.prototype;p.clone=function(){return new Fd(this.x,this.y)};
p.equals=function(a){return a instanceof Fd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
p.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
p.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
p.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
p.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function Gd(a,b){this.width=a;this.height=b}
p=Gd.prototype;p.clone=function(){return new Gd(this.width,this.height)};
p.aspectRatio=function(){return this.width/this.height};
p.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
p.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
p.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
p.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function Hd(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function Id(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function Jd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Kd;function Ld(){var a=C.MessageChannel;typeof a==="undefined"&&typeof window!=="undefined"&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=Id("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h=f.location.protocol=="file:"?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if((h=="*"||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if(typeof a!=="undefined"){var b=new a,c={},d=c;b.port1.onmessage=function(){if(c.next!==void 0){c=c.next;var e=c.Sc;c.Sc=null;e()}};
return function(e){d.next={Sc:e};d=d.next;b.port2.postMessage(0)}}return function(e){C.setTimeout(e,0)}}
;function Md(a){C.setTimeout(function(){throw a;},0)}
;function Nd(){this.i=this.h=null}
Nd.prototype.add=function(a,b){var c=Od.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Nd.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Od=new Bd(function(){return new Pd},function(a){return a.reset()});
function Pd(){this.next=this.scope=this.h=null}
Pd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Pd.prototype.reset=function(){this.next=this.scope=this.h=null};var Qd,Rd=!1,Sd=new Nd;function Td(a,b){Qd||Ud();Rd||(Qd(),Rd=!0);Sd.add(a,b)}
function Ud(){if(C.Promise&&C.Promise.resolve){var a=C.Promise.resolve(void 0);Qd=function(){a.then(Vd)}}else Qd=function(){var b=Vd;
typeof C.setImmediate!=="function"||C.Window&&C.Window.prototype&&C.Window.prototype.setImmediate==C.setImmediate?(Kd||(Kd=Ld()),Kd(b)):C.setImmediate(b)}}
function Vd(){for(var a;a=Sd.remove();){try{a.h.call(a.scope)}catch(b){Md(b)}Cd(Od,a)}Rd=!1}
;function Wd(a){this.h=0;this.A=void 0;this.l=this.i=this.j=null;this.v=this.m=!1;if(a!=Dd)try{var b=this;a.call(void 0,function(c){Xd(b,2,c)},function(c){Xd(b,3,c)})}catch(c){Xd(this,3,c)}}
function Yd(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Yd.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Zd=new Bd(function(){return new Yd},function(a){a.reset()});
function $d(a,b,c){var d=Zd.get();d.i=a;d.h=b;d.context=c;return d}
function ae(a){return new Wd(function(b,c){c(a)})}
Wd.prototype.then=function(a,b,c){return be(this,typeof a==="function"?a:null,typeof b==="function"?b:null,c)};
Wd.prototype.$goog_Thenable=!0;p=Wd.prototype;p.oc=function(a,b){return be(this,null,a,b)};
p.catch=Wd.prototype.oc;p.cancel=function(a){if(this.h==0){var b=new ce(a);Td(function(){de(this,b)},this)}};
function de(a,b){if(a.h==0)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.h==0&&d==1?de(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):ee(c),fe(c,e,3,b)))}a.j=null}else Xd(a,3,b)}
function ge(a,b){a.i||a.h!=2&&a.h!=3||he(a);a.l?a.l.next=b:a.i=b;a.l=b}
function be(a,b,c,d){var e=$d(null,null,null);e.child=new Wd(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof ce?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;ge(a,e);return e.child}
p.cf=function(a){this.h=0;Xd(this,2,a)};
p.df=function(a){this.h=0;Xd(this,3,a)};
function Xd(a,b,c){if(a.h==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.cf,f=a.df;if(d instanceof Wd){ge(d,$d(e||Dd,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if(typeof k==="function"){ie(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.A=c,a.h=b,a.j=null,he(a),b!=3||c instanceof ce||je(a,c))}}
function ie(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function he(a){a.m||(a.m=!0,Td(a.Sd,a))}
function ee(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
p.Sd=function(){for(var a;a=ee(this);)fe(this,a,this.h,this.A);this.m=!1};
function fe(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.v;a=a.j)a.v=!1;if(b.child)b.child.j=null,ke(b,c,d);else try{b.j?b.i.call(b.context):ke(b,c,d)}catch(e){le.call(null,e)}Cd(Zd,b)}
function ke(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function je(a,b){a.v=!0;Td(function(){a.v&&le.call(null,b)})}
var le=Md;function ce(a){bb.call(this,a)}
$a(ce,bb);ce.prototype.name="cancel";function me(a,b){yd.call(this);this.j=a||1;this.i=b||C;this.l=Xa(this.Ze,this);this.m=Za()}
$a(me,yd);p=me.prototype;p.enabled=!1;p.Fa=null;p.setInterval=function(a){this.j=a;this.Fa&&this.enabled?(this.stop(),this.start()):this.Fa&&this.stop()};
p.Ze=function(){if(this.enabled){var a=Za()-this.m;a>0&&a<this.j*.8?this.Fa=this.i.setTimeout(this.l,this.j-a):(this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null),zd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
p.start=function(){this.enabled=!0;this.Fa||(this.Fa=this.i.setTimeout(this.l,this.j),this.m=Za())};
p.stop=function(){this.enabled=!1;this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null)};
p.U=function(){me.Ba.U.call(this);this.stop();delete this.i};
function ne(a,b,c){if(typeof a==="function")c&&(a=Xa(a,c));else if(a&&typeof a.handleEvent=="function")a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return Number(b)>2147483647?-1:C.setTimeout(a,b||0)}
;function oe(a){G.call(this);this.H=a;this.j=0;this.l=100;this.m=!1;this.i=new Map;this.A=new Set;this.flushInterval=3E4;this.h=new me(this.flushInterval);this.h.listen("tick",this.Aa,!1,this);Ec(this,this.h)}
y(oe,G);p=oe.prototype;p.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function pe(a){a.h.enabled||a.h.start();a.j++;a.j>=a.l&&a.Aa()}
p.Aa=function(){var a=this.i.values();a=[].concat(la(a)).filter(function(b){return b.h.size});
a.length&&this.H.flush(a,this.m);qe(a);this.j=0;this.h.enabled&&this.h.stop()};
p.Ra=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Ac(a,b))};
p.Fb=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Bc(a,b))};
function re(a,b){return a.A.has(b)?void 0:a.i.get(b)}
p.Bb=function(a){this.Fd(a,1,B.apply(1,arguments))};
p.Fd=function(a,b){var c=B.apply(2,arguments),d=re(this,a);d&&d instanceof Ac&&(d.i(b,c),pe(this))};
p.record=function(a,b){var c=B.apply(2,arguments),d=re(this,a);d&&d instanceof Bc&&(d.record(b,c),pe(this))};
function qe(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function se(a){this.h=a;this.h.Ra("/client_streamz/bg/fic",{G:3,F:"ke"})}
function te(a){this.h=a;this.h.Ra("/client_streamz/bg/fiec",{G:3,F:"rk"},{G:3,F:"ke"},{G:2,F:"ec"})}
function ue(a){this.h=a;this.h.Fb("/client_streamz/bg/fil",{G:3,F:"rk"},{G:3,F:"ke"})}
ue.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fil",a,b,c)};
function ve(a){this.h=a;this.h.Ra("/client_streamz/bg/fcc",{G:2,F:"ph"},{G:3,F:"ke"})}
function we(a){this.h=a;this.h.Fb("/client_streamz/bg/fcd",{G:2,F:"ph"},{G:3,F:"ke"})}
we.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fcd",a,b,c)};
function xe(a){this.h=a;this.h.Ra("/client_streamz/bg/fsc",{G:3,F:"rk"},{G:3,F:"ke"})}
function ye(a){this.h=a;this.h.Fb("/client_streamz/bg/fsl",{G:3,F:"rk"},{G:3,F:"ke"})}
ye.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fsl",a,b,c)};
function ze(a){this.h=a;this.h.Fb("/client_streamz/bg/wrl",{G:3,F:"mn"},{G:2,F:"ac"},{G:2,F:"sc"},{G:3,F:"rk"},{G:3,F:"mk"})}
ze.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Ae(a){this.h=a;this.h.Fb("/client_streamz/bg/el",{G:3,F:"en"},{G:3,F:"bk"},{G:3,F:"rk"},{G:3,F:"mk"})}
Ae.prototype.record=function(a,b,c,d,e){this.h.record("/client_streamz/bg/el",a,b,c,d,e)};
function Be(a){this.h=a;this.h.Ra("/client_streamz/bg/cec",{G:2,F:"ec"},{G:3,F:"bk"},{G:3,F:"rk"},{G:3,F:"mk"})}
function Ce(a){this.h=a;this.h.Ra("/client_streamz/bg/po/csc",{G:2,F:"cs"},{G:3,F:"rk"},{G:3,F:"mk"})}
function De(a){this.h=a;this.h.Ra("/client_streamz/bg/po/ctav",{G:3,F:"av"},{G:3,F:"rk"},{G:3,F:"mk"})}
function Ee(a){this.h=a;this.h.Ra("/client_streamz/bg/po/cwsc",{G:3,F:"su"},{G:3,F:"rk"},{G:3,F:"mk"})}
;Rc();var Fe=Uc()||H("iPod"),Ge=H("iPad");!H("Android")||Sc()||Rc()||Qc()||H("Silk");Sc();var He=H("Safari")&&!(Sc()||(Pc()?0:H("Coast"))||Qc()||(Pc()?0:H("Edge"))||(Pc()?Oc("Microsoft Edge"):H("Edg/"))||(Pc()?Oc("Opera"):H("OPR"))||Rc()||H("Silk")||H("Android"))&&!(Uc()||H("iPad")||H("iPod"));var Ie={},Je=null;function Ke(a,b){Qa(a);b===void 0&&(b=0);Le();b=Ie[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function Me(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;Ne(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function Ne(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),n=Je[l];if(n!=null)return n;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Le();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function Le(){if(!Je){Je={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));Ie[c]=d;for(var e=0;e<d.length;e++){var f=d[e];Je[f]===void 0&&(Je[f]=e)}}}}
;var Oe=typeof Uint8Array!=="undefined",Pe=!Xc&&typeof btoa==="function";function Qe(a){if(!Pe)return Ke(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Re=/[-_.]/g,Se={"-":"+",_:"/",".":"="};function Te(a){return Se[a]||""}
function Ue(a){return Oe&&a!=null&&a instanceof Uint8Array}
var Ve={};var We;function Xe(a){if(a!==Ve)throw Error("illegal external caller");}
function Ye(a,b){Xe(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
Ye.prototype.sizeBytes=function(){Xe(Ve);var a=this.h;if(a!=null&&!Ue(a))if(typeof a==="string")if(Pe){Re.test(a)&&(a=a.replace(Re,Te));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=Me(a);else Pa(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};function Ze(){return typeof BigInt==="function"}
;var $e=0,af=0;function bf(a){var b=a>>>0;$e=b;af=(a-b)/4294967296>>>0}
function cf(a){if(a<0){bf(0-a);var b=x(df($e,af));a=b.next().value;b=b.next().value;$e=a>>>0;af=b>>>0}else bf(a)}
function ef(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else Ze()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+ff(c)+ff(a));return c}
function ff(a){a=String(a);return"0000000".slice(a.length)+a}
function gf(){var a=$e,b=af;b&2147483648?Ze()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=x(df(a,b)),a=b.next().value,b=b.next().value,a="-"+ef(a,b)):a=ef(a,b);return a}
function df(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function hf(a){return Array.prototype.slice.call(a)}
;var jf=typeof Symbol==="function"&&typeof Symbol()==="symbol";function kf(a){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?Symbol():a}
var lf=kf(),mf=kf("2ex"),nf=kf("1oa");Math.max.apply(Math,la(Object.values({qg:1,og:2,ng:4,tg:8,sg:16,rg:32,uf:64,vg:128,mg:256,lg:512,pg:1024,zf:2048,ug:4096,Af:8192})));var of=jf?function(a,b){a[lf]|=b}:function(a,b){a.Ua!==void 0?a.Ua|=b:Object.defineProperties(a,{Ua:{value:b,
configurable:!0,writable:!0,enumerable:!1}})},pf=jf?function(a){return a[lf]|0}:function(a){return a.Ua|0},qf=jf?function(a){return a[lf]}:function(a){return a.Ua},rf=jf?function(a,b){a[lf]=b}:function(a,b){a.Ua!==void 0?a.Ua=b:Object.defineProperties(a,{Ua:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function sf(a,b){rf(b,(a|0)&-14591)}
function tf(a,b){rf(b,(a|34)&-14557)}
;var uf={},vf={};function wf(a){return!(!a||typeof a!=="object"||a.h!==vf)}
function xf(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
function yf(a,b,c){if(!Array.isArray(a)||a.length)return!1;var d=pf(a);if(d&1)return!0;if(!(b&&(Array.isArray(b)?b.includes(c):b.has(c))))return!1;rf(a,d|1);return!0}
var zf,Af=[];rf(Af,55);zf=Object.freeze(Af);function Bf(a){if(a&2)throw Error();}
Object.freeze({});Object.freeze({});var Cf=Object.freeze({});var Df;function Ef(){var a=Error();ec(a,"incident");Md(a)}
function Ff(a){a=Error(a);ec(a,"warning");return a}
;function Gf(a){return a.displayName||a.name||"unknown type name"}
function Hf(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+Pa(a)+": "+a);return a}
var If=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function Jf(a){var b=typeof a;return b==="number"?Number.isFinite(a):b!=="string"?!1:If.test(a)}
function Kf(a){if(typeof a!=="number")throw Ff("int32");if(!Number.isFinite(a))throw Ff("int32");return a|0}
function Lf(a){return a==null?a:Kf(a)}
function Mf(a){if(a==null)return a;if(typeof a==="string"){if(!a)return;a=+a}if(typeof a==="number")return Number.isFinite(a)?a|0:void 0}
function Nf(a){if(a!=null){var b=!!b;if(!Jf(a))throw Ff("int64");a=typeof a==="string"?Of(a):b?Pf(a):Qf(a)}return a}
function Rf(a){return a[0]==="-"?a.length<20?!0:a.length===20&&Number(a.substring(0,7))>-922337:a.length<19?!0:a.length===19&&Number(a.substring(0,6))<922337}
function Qf(a){Jf(a);a=Math.trunc(a);if(!Number.isSafeInteger(a)){cf(a);var b=$e,c=af;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);b=c*4294967296+(b>>>0);a=a?-b:b}return a}
function Pf(a){Jf(a);a=Math.trunc(a);if(Number.isSafeInteger(a))a=String(a);else{var b=String(a);Rf(b)?a=b:(cf(a),a=gf())}return a}
function Of(a){Jf(a);var b=Math.trunc(Number(a));if(Number.isSafeInteger(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));a.indexOf(".");if(!Rf(a)){if(a.length<16)cf(Number(a));else if(Ze())a=BigInt(a),$e=Number(a&BigInt(4294967295))>>>0,af=Number(a>>BigInt(32)&BigInt(4294967295));else{b=+(a[0]==="-");af=$e=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),af*=1E6,$e=$e*1E6+d,$e>=4294967296&&(af+=Math.trunc($e/4294967296),af>>>=0,$e>>>=0);b&&(b=x(df($e,af)),
a=b.next().value,b=b.next().value,$e=a,af=b)}a=gf()}return a}
function Sf(a){if(typeof a!=="string")throw Error();return a}
function Tf(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Uf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Gf(b)+" but got "+(a&&Gf(a.constructor)));}
function Vf(a,b,c){if(a!=null&&typeof a==="object"&&a.Cc===uf)return a;if(Array.isArray(a)){var d=pf(a),e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&rf(a,e);return new b(a)}}
;var Wf;function Xf(a,b){pf(b);Wf=b;a=new a(b);Wf=void 0;return a}
function J(a,b,c){a==null&&(a=Wf);Wf=void 0;if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-16760833|(b&1023)<<14)}else{if(!Array.isArray(a))throw Error("narr");d=pf(a);if(d&2048)throw Error("farr");if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1;if(xf(c[f])){d|=256;b=f-(+!!(d&512)-1);if(b>=1024)throw Error("pvtlmt");d=d&-16760833|(b&1023)<<14;break a}}if(b){b=Math.max(b,e-(+!!(d&512)-1));if(b>1024)throw Error("spvt");d=d&-16760833|(b&1023)<<
14}}}rf(a,d);return a}
;function Yf(a){if(typeof Proxy!=="function")return a;var b=Zf(a);if(b)return b;b=new Proxy(a,{set:function(c,d,e){$f();c[d]=e;return!0}});
ag(a,b);return b}
function $f(){Ef()}
var bg=void 0,cg=void 0;function Zf(a){var b;return(b=bg)==null?void 0:b.get(a)}
function dg(a){var b;return((b=cg)==null?void 0:b.get(a))||a}
function ag(a,b){(bg||(bg=new WeakMap)).set(a,b);(cg||(cg=new WeakMap)).set(b,a)}
;function eg(a,b){return fg(b)}
function fg(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a)if(Array.isArray(a)){if(yf(a,void 0,0))return}else{if(Ue(a))return Qe(a);if(a instanceof Ye){var b=a.h;return b==null?"":typeof b==="string"?b:a.h=Qe(b)}}}return a}
;function gg(a,b,c){a=hf(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function hg(a,b,c,d,e){if(a!=null){if(Array.isArray(a))a=yf(a,void 0,0)?void 0:e&&pf(a)&2?a:ig(a,b,c,d!==void 0,e);else if(xf(a)){var f={},g;for(g in a)f[g]=hg(a[g],b,c,d,e);a=f}else a=b(a,d);return a}}
function ig(a,b,c,d,e){var f=d||c?pf(a):0;d=d?!!(f&32):void 0;a=hf(a);for(var g=0;g<a.length;g++)a[g]=hg(a[g],b,c,d,e);c&&c(f,a);return a}
function jg(a){return a.Cc===uf?a.toJSON():fg(a)}
;function kg(a,b,c){c=c===void 0?tf:c;if(a!=null){if(Oe&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=pf(a);if(d&2)return a;b&&(b=d===0||!!(d&32)&&!(d&64||!(d&16)));return b?(rf(a,(d|34)&-12293),a):ig(a,kg,d&4?tf:c,!0,!0)}a.Cc===uf&&(c=a.D,d=qf(c),a=d&2?a:Xf(a.constructor,lg(c,d,!0)));return a}}
function lg(a,b,c){var d=c||b&2?tf:sf,e=!!(b&32);a=gg(a,b,function(f){return kg(f,e,d)});
of(a,32|(c?2:0));return a}
function mg(a){var b=a.D,c=qf(b);return c&2?Xf(a.constructor,lg(b,c,!1)):a}
;function ng(a,b){a=a.D;return og(a,qf(a),b)}
function pg(a,b,c,d){b=d+(+!!(b&512)-1);if(!(b<0||b>=a.length||b>=c))return a[b]}
function og(a,b,c,d){if(c===-1)return null;var e=b>>14&1023||536870912;if(c>=e){if(b&256)return a[a.length-1][c]}else{var f=a.length;if(d&&b&256&&(d=a[f-1][c],d!=null)){if(pg(a,b,e,c)&&mf!=null){var g;a=(g=Df)!=null?g:Df={};g=a[mf]||0;g>=4||(a[mf]=g+1,Ef())}return d}return pg(a,b,e,c)}}
function K(a,b,c){var d=a.D,e=qf(d);Bf(e);qg(d,e,b,c);return a}
function qg(a,b,c,d,e){xf(d);var f=b>>14&1023||536870912;if(c>=f||e&&!Kc){var g=b;if(b&256)e=a[a.length-1];else{if(d==null)return g;e=a[f+(+!!(b&512)-1)]={};g|=256}e[c]=d;c<f&&(a[c+(+!!(b&512)-1)]=void 0);g!==b&&rf(a,g);return g}a[c+(+!!(b&512)-1)]=d;b&256&&(a=a[a.length-1],c in a&&delete a[c]);return b}
function rg(a){return sg(a,tg,11,!1)!==void 0}
function ug(a){return!!(2&a)&&!!(4&a)||!!(2048&a)}
function vg(a,b,c){var d=a.D,e=qf(d);Bf(e);if(b==null)return qg(d,e,3),a;b=dg(b);if(!Array.isArray(b))throw Ff();var f=pf(b),g=f,h=!!(2&f)||Object.isFrozen(b),k=!h&&(void 0===Cf||!1);if(!(4&f))for(f=21,h&&(b=hf(b),g=0,f=wg(f,e),f=xg(f,e,!0)),h=0;h<b.length;h++)b[h]=c(b[h]);k&&(b=hf(b),g=0,f=wg(f,e),f=xg(f,e,!0));f!==g&&rf(b,f);qg(d,e,3,b);return a}
function yg(a,b,c,d){a=a.D;var e=qf(a);Bf(e);if(d==null){var f=zg(a);if(Ag(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=zg(a);var g=Ag(f,a,e,c);g!==b&&(g&&(e=qg(a,e,g)),f.set(c,b))}qg(a,e,b,d)}
function zg(a){if(jf){var b;return(b=a[nf])!=null?b:a[nf]=new Map}if(nf in a)return a[nf];b=new Map;Object.defineProperty(a,nf,{value:b});return b}
function Ag(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];og(b,c,g)!=null&&(e!==0&&(c=qg(b,c,e)),e=g)}a.set(d,e);return e}
function sg(a,b,c,d){a=a.D;var e=qf(a),f=og(a,e,c,d);b=Vf(f,b,e);b!==f&&b!=null&&qg(a,e,c,b,d);return b}
function Bg(a,b,c,d){d=d===void 0?!1:d;b=sg(a,b,c,d);if(b==null)return b;a=a.D;var e=qf(a);if(!(e&2)){var f=mg(b);f!==b&&(b=f,qg(a,e,c,b,d))}return b}
function Cg(a,b,c,d){d!=null?Uf(d,b):d=void 0;return K(a,c,d)}
function Dg(a,b,c,d){var e=a.D,f=qf(e);Bf(f);if(d==null)return qg(e,f,c),a;d=dg(d);if(!Array.isArray(d))throw Ff();for(var g=pf(d),h=g,k=!!(2&g)||!!(2048&g),l=k||Object.isFrozen(d),n=!l&&(void 0===Cf||!1),m=!0,r=!0,t=0;t<d.length;t++){var v=d[t];Uf(v,b);k||(v=!!(pf(v.D)&2),m&&(m=!v),r&&(r=v))}k||(g|=5,g=m?g|8:g&-9,g=r?g|16:g&-17);if(n||l&&g!==h)d=hf(d),h=0,g=wg(g,f),g=xg(g,f,!0);g!==h&&rf(d,g);qg(e,f,c,d);return a}
function wg(a,b){a=(2&b?a|2:a&-3)|32;return a&=-2049}
function xg(a,b,c){32&b&&c||(a&=-33);return a}
function Eg(a,b){a=ng(a,b);var c;a==null?c=a:Jf(a)?typeof a==="number"?c=Qf(a):c=Of(a):c=void 0;return c}
function Fg(a){a=ng(a,1);var b=b===void 0?!1:b;b=a==null?a:Jf(a)?typeof a==="string"?Of(a):b?Pf(a):Qf(a):void 0;return b}
function Gg(a){var b=0;b=b===void 0?0:b;a=ng(a,1);a=a==null?a:Number.isFinite(a)?a|0:void 0;return a!=null?a:b}
function Hg(a,b,c){return K(a,b,Tf(c))}
function Ig(a,b,c){if(c!=null){if(!Number.isFinite(c))throw Ff("enum");c|=0}return K(a,b,c)}
;function Jg(a){return a}
function Kg(a){return a}
function Lg(a,b,c,d){return Mg(a,b,c,d,Ng,Qg)}
function Rg(a,b,c,d){return Mg(a,b,c,d,Sg,Tg)}
function Mg(a,b,c,d,e,f){if(!c.length&&!d)return 0;for(var g=0,h=0,k=0,l=0,n=0,m=c.length-1;m>=0;m--){var r=c[m];d&&m===c.length-1&&r===d||(l++,r!=null&&k++)}if(d)for(var t in d)m=+t,isNaN(m)||(n+=Ug(m),h++,m>g&&(g=m));l=e(l,k)+f(h,g,n);t=k;m=h;r=g;for(var v=n,u=c.length-1;u>=0;u--){var z=c[u];if(!(z==null||d&&u===c.length-1&&z===d)){z=u-b;var F=e(z,t)+f(m,r,v);F<l&&(a=1+z,l=F);m++;t--;v+=Ug(z);r=Math.max(r,z)}}b=e(0,0)+f(m,r,v);b<l&&(a=0,l=b);if(d){m=h;r=g;v=n;t=k;for(var I in d)d=+I,isNaN(d)||d>=
1024||(m--,t++,v-=I.length,g=e(d,t)+f(m,r,v),g<l&&(a=1+d,l=g))}return a}
function Tg(a,b,c){return c+a*3+(a>1?a-1:0)}
function Sg(a,b){return(a>1?a-1:0)+(a-b)*4}
function Qg(a,b){return a==0?0:9*Math.max(1<<32-Math.clz32(a+a/2-1),4)<=b?a==0?0:a<4?100+(a-1)*16:a<6?148+(a-4)*16:a<12?244+(a-6)*16:a<22?436+(a-12)*19:a<44?820+(a-22)*17:52+32*a:40+4*b}
function Ng(a){return 40+4*a}
function Ug(a){return a>=100?a>=1E4?Math.ceil(Math.log10(1+a)):a<1E3?3:4:a<10?1:2}
;var Vg,Wg;function L(a,b,c){this.D=J(a,b,c)}
p=L.prototype;p.toJSON=function(){return Xg(this)};
p.serialize=function(a){try{return Wg=!0,a&&(Vg=a===Kg||a!==Jg&&a!==Lg&&a!==Rg?Kg:a),JSON.stringify(Xg(this),eg)}finally{a&&(Vg=void 0),Wg=!1}};
function Yg(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");of(b,32);return Xf(a,b)}
p.clone=function(){var a=this.D,b=qf(a);return Xf(this.constructor,lg(a,b,!1))};
p.Cc=uf;p.toString=function(){try{return Wg=!0,Xg(this).toString()}finally{Wg=!1}};
function Xg(a){var b;Wg?b=a.D:b=ig(a.D,jg,void 0,void 0,!1);var c=!Wg;var d=Jc?void 0:a.constructor.Qa;var e=qf(c?a.D:b);if(a=b.length){var f=b[a-1],g=xf(f);g?a--:f=void 0;var h=+!!(e&512)-1,k=a-h,l=!!Vg&&Kc&&!(e&512),n;e=(n=Vg)!=null?n:Kg;e=l?e(k,h,b,f):k;k=(n=l&&k!==e)?Array.prototype.slice.call(b,0,a):b;if(g||n){b:{var m=k;var r=f;g={};l=!1;if(n)for(var t=Math.max(0,e+h);t<m.length;t++){var v=m[t],u=t-h;v==null||yf(v,d,u)||wf(v)&&v.size===0||(m[t]=void 0,g[u]=v,l=!0)}if(r)for(var z in r)if(t=+z,
isNaN(t))g[z]=r[z];else if(v=r[z],Array.isArray(v)&&(yf(v,d,+z)||wf(v)&&v.size===0)&&(v=null),v==null&&(l=!0),n&&t<e){l=!0;v=t+h;for(u=m.length;u<=v;u++)m.push(void 0);m[v]=r[t]}else v!=null&&(g[z]=v);if(l){for(var F in g){r=g;break b}r=null}}m=r==null?f!=null:r!==f}n&&(a=k.length);for(;a>0;a--){F=a-1;z=k[F];F-=h;if(!(z==null||yf(z,d,F)||wf(z)&&z.size===0))break;var I=!0}if(k!==b||m||I){if(!n&&!c)k=Array.prototype.slice.call(k,0,a);else if(I||m||r)k.length=a;r&&k.push(r)}I=k}else I=b;return I}
;function Zg(a){a.Fg=!0;return a}
;function $g(a){this.D=J(a)}
y($g,L);$g.Qa=[1,2,3,4];var ah={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);a>0;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function bh(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=ch(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;g>=12;g-=12,h+=12)c+=dh(a,h),d+=dh(a,h+4),e+=dh(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return ah.toString(e)}
function ch(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function dh(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function eh(a){this.D=J(a)}
y(eh,L);var fh=[1,2,3];function gh(a){this.D=J(a)}
y(gh,L);var hh=[1,2,3];function ih(a){this.D=J(a)}
y(ih,L);ih.Qa=[1];function jh(a){this.D=J(a)}
y(jh,L);jh.Qa=[3,6,4];function kh(a){this.D=J(a)}
y(kh,L);kh.Qa=[1];function lh(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function mh(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(m){for(var r=g,t=0;t<64;t+=4)r[t/4]=m[t]<<24|m[t+1]<<16|m[t+2]<<8|m[t+3];for(t=16;t<80;t++)m=r[t-3]^r[t-8]^r[t-14]^r[t-16],r[t]=(m<<1|m>>>31)&4294967295;m=e[0];var v=e[1],u=e[2],z=e[3],F=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var I=z^v&(u^z);var O=1518500249}else I=v^u^z,O=1859775393;else t<60?(I=v&u|z&(v|u),O=2400959708):(I=v^u^z,O=3395469782);I=((m<<5|m>>>27)&4294967295)+I+F+O+r[t]&4294967295;F=z;z=u;u=(v<<30|v>>>2)&4294967295;v=m;m=I}e[0]=e[0]+m&4294967295;e[1]=e[1]+v&4294967295;e[2]=
e[2]+u&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+F&4294967295}
function c(m,r){if(typeof m==="string"){m=unescape(encodeURIComponent(m));for(var t=[],v=0,u=m.length;v<u;++v)t.push(m.charCodeAt(v));m=t}r||(r=m.length);t=0;if(l==0)for(;t+64<r;)b(m.slice(t,t+64)),t+=64,n+=64;for(;t<r;)if(f[l++]=m[t++],n++,l==64)for(l=0,b(f);t+64<r;)b(m.slice(t,t+64)),t+=64,n+=64}
function d(){var m=[],r=n*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=r&255,r>>>=8;b(f);for(t=r=0;t<5;t++)for(var v=24;v>=0;v-=8)m[r++]=e[t]>>v&255;return m}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,Od:function(){for(var m=d(),r="",t=0;t<m.length;t++)r+="0123456789ABCDEF".charAt(Math.floor(m[t]/16))+"0123456789ABCDEF".charAt(m[t]%16);return r}}}
;function nh(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,oh(lh(d),a,c||null)].join(" "):null}
function oh(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Db(d,function(h){e.push(h)}),ph(e.join(" "));
var f=[],g=[];Db(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Db(d,function(h){e.push(h)});
a=ph(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function ph(a){var b=mh();b.update(a);return b.Od().toLowerCase()}
;var qh={};function rh(a){this.h=a||{cookie:""}}
p=rh.prototype;p.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Nb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
p.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.Ge;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Nb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
p.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=db(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
p.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Nb:0,path:b,domain:c});return d};
p.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=db(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var sh=new rh(typeof document=="undefined"?null:document);function th(a){return!!qh.FPA_SAMESITE_PHASE2_MOD||!(a===void 0||!a)}
function uh(a){a=a===void 0?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;th(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if(typeof document!=="undefined"){var c=new rh(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID");th(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function vh(a,b,c,d){(a=C[a])||typeof document==="undefined"||(a=(new rh(document)).get(b));return a?nh(a,c,d):null}
function wh(a,b){b=b===void 0?!1:b;var c=lh(String(C.location.href)),d=[];if(uh(b)){c=c.indexOf("https:")==0||c.indexOf("chrome-extension:")==0||c.indexOf("chrome-untrusted://new-tab-page")==0||c.indexOf("moz-extension:")==0;var e=c?C.__SAPISID:C.__APISID;e||typeof document==="undefined"||(e=new rh(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?nh(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&th(b)&&((b=vh("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),
(a=vh("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return d.length==0?null:d.join(" ")}
;function xh(a){this.D=J(a)}
y(xh,L);xh.Qa=[2];function yh(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return Za()};
this.i=this.h()}
yh.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
yh.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
yh.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
yh.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function zh(a){this.D=J(a)}
y(zh,L);function Ah(a){this.D=J(a)}
y(Ah,L);function Bh(a){this.h=this.i=this.j=a}
Bh.prototype.reset=function(){this.h=this.i=this.j};
Bh.prototype.getValue=function(){return this.i};function Ch(a){this.D=J(a)}
y(Ch,L);Ch.prototype.dc=function(){return Gg(this)};function Dh(a){this.D=J(a)}
y(Dh,L);function Eh(a){this.D=J(a)}
y(Eh,L);function Fh(a,b){Dg(a,Dh,1,b)}
Eh.Qa=[1];function tg(a){this.D=J(a)}
y(tg,L);var Gh=["platform","platformVersion","architecture","model","uaFullVersion"],Hh=new Eh,Ih=null;function Jh(a,b){b=b===void 0?Gh:b;if(!Ih){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new Dh;f=Hg(f,1,e.brand);return Hg(f,2,e.version)});
Fh(K(Hh,2,Hf(a.mobile)),c);Ih=a.getHighEntropyValues(b)}var d=new Set(b);return Ih.then(function(e){var f=Hh.clone();d.has("platform")&&Hg(f,3,e.platform);d.has("platformVersion")&&Hg(f,4,e.platformVersion);d.has("architecture")&&Hg(f,5,e.architecture);d.has("model")&&Hg(f,6,e.model);d.has("uaFullVersion")&&Hg(f,7,e.uaFullVersion);return f}).catch(function(){return Hh.clone()})}
;function Kh(a){this.D=J(a)}
y(Kh,L);function Lh(a){this.D=J(a,4)}
y(Lh,L);function Mh(a){this.D=J(a,35)}
y(Mh,L);Mh.Qa=[3,20,27];function Nh(a){this.D=J(a,19)}
y(Nh,L);Nh.prototype.Qb=function(a){return Ig(this,2,a)};
Nh.Qa=[3,5];function Oh(a){this.D=J(a,8)}
y(Oh,L);var Ph=function(a){return function(b){return Yg(a,b)}}(Oh);
Oh.Qa=[5,6,7];function Qh(a){this.D=J(a)}
y(Qh,L);var Rh=new function(){this.ctor=Qh;this.isRepeated=0;this.h=Bg;this.defaultValue=void 0};function Sh(a){G.call(this);var b=this;this.componentId="";this.j=[];this.da="";this.pageId=null;this.ga=this.W=-1;this.experimentIds=null;this.P=this.m=0;this.ia=1;this.timeoutMillis=0;this.logSource=a.logSource;this.Kb=a.Kb||function(){};
this.i=new Th(a.logSource,a.eb);this.network=a.network;this.zb=a.zb||null;this.bufferSize=1E3;this.A=a.ef||null;this.sessionIndex=a.sessionIndex||null;this.Ib=a.Ib||!1;this.logger=null;this.withCredentials=!a.Vc;this.eb=a.eb||!1;this.H=typeof URLSearchParams!=="undefined"&&!!(new URL(Uh())).searchParams&&!!(new URL(Uh())).searchParams.set;var c=Ig(new Kh,1,1);Vh(this.i,c);this.l=new Bh(1E4);a=Wh(this,a.Pc);this.h=new yh(this.l.getValue(),a);this.ba=new yh(6E5,a);this.Ib||this.ba.start();this.eb||
(document.addEventListener("visibilitychange",function(){document.visibilityState==="hidden"&&b.uc()}),document.addEventListener("pagehide",this.uc.bind(this)))}
y(Sh,G);function Wh(a,b){return a.H?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
p=Sh.prototype;p.U=function(){this.uc();this.h.stop();this.ba.stop();G.prototype.U.call(this)};
p.log=function(a){if(this.H){a=a.clone();var b=this.ia++;a=K(a,21,Nf(b));this.componentId&&Hg(a,26,this.componentId);if(Fg(a)==null){var c=Date.now();b=a;c=Number.isFinite(c)?c.toString():"0";K(b,1,Nf(c))}Eg(a,15)==null&&K(a,15,Nf((new Date).getTimezoneOffset()*60));this.experimentIds&&(b=a,c=this.experimentIds.clone(),Cg(b,xh,16,c));b=this.j.length-this.bufferSize+1;b>0&&(this.j.splice(0,b),this.m+=b);this.j.push(a);this.Ib||this.h.enabled||this.h.start()}};
p.flush=function(a,b){var c=this;if(this.j.length===0)a&&a();else{var d=Date.now();if(this.ga>d&&this.W<d)b&&b("throttled");else{this.network&&(typeof this.network.dc==="function"?Xh(this.i,this.network.dc()):Xh(this.i,0));var e=Yh(this.i,this.j,this.m,this.P,this.zb);d={};var f=this.Kb();f&&(d.Authorization=f);this.A||(this.A=Uh());try{var g=(new URL(this.A)).toString()}catch(k){g=(new URL(this.A,window.location.origin)).toString()}g=new URL(g);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,
g.searchParams.set("authuser",this.sessionIndex));this.pageId&&(Object.defineProperty(d,"X-Goog-PageId",{value:this.pageId}),g.searchParams.set("pageId",this.pageId));if(f&&this.da===f)b&&b("stale-auth-token");else{this.j=[];this.h.enabled&&this.h.stop();this.m=0;var h=e.serialize();d={url:g.toString(),body:h,yg:1,pd:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis};g=function(k){c.l.reset();c.h.setInterval(c.l.getValue());if(k){var l=null;try{var n=JSON.stringify(JSON.parse(k.replace(")]}'\n",
"")));l=Ph(n)}catch(r){}if(l){k=Number;n="-1";n=n===void 0?"0":n;var m=Fg(l);k=k(m!=null?m:n);k>0&&(c.W=Date.now(),c.ga=c.W+k);l=Rh.ctor?Rh.h(l,Rh.ctor,175237375,!0):Rh.h(l,175237375,null,!0);if(k=l===null?void 0:l)l=-1,l=l===void 0?0:l,k=Mf(ng(k,1)),l=k!=null?k:l,l!==-1&&(c.l=new Bh(l<1?1:l),c.h.setInterval(c.l.getValue()))}}a&&a();c.P=0};
h=function(k,l){var n=e.D,m=qf(n);var r=m;var t=!(2&m),v=(m=!!(2&r))?1:2;t&&(t=!m);m=og(n,r,3);m=Array.isArray(m)?m:zf;var u=pf(m),z=!!(4&u);if(!z){var F=u;F===0&&(F=wg(F,r));u=m;F|=1;var I=r,O=!!(2&F);O&&(I|=2);for(var S=!O,da=!0,ta=0,P=0;ta<u.length;ta++){var ea=Vf(u[ta],Mh,I);if(ea instanceof Mh){if(!O){var na=!!(pf(ea.D)&2);S&&(S=!na);da&&(da=na)}u[P++]=ea}}P<ta&&(u.length=P);F|=4;F=da?F|16:F&-17;F=S?F|8:F&-9;rf(u,F);O&&Object.freeze(u);u=F}if(t&&!(8&u||!m.length&&(v===1||v===4&&32&u))){ug(u)&&
(m=hf(m),u=wg(u,r),r=qg(n,r,3,m));t=m;for(F=0;F<t.length;F++)I=t[F],O=mg(I),I!==O&&(t[F]=O);u|=8;u=t.length?u&-17:u|16;rf(t,u)}v===1||v===4&&32&u?ug(u)||(r=u,n=!!(32&u),u|=!m.length||16&u&&(!z||n)?2:2048,u!==r&&rf(m,u),Object.freeze(m)):(z=v!==5?!1:!!(32&u)||ug(u)||!!Zf(m),(v===2||z)&&ug(u)&&(m=hf(m),u=wg(u,r),u=xg(u,r,!1),rf(m,u),r=qg(n,r,3,m)),ug(u)||(n=u,u=xg(u,r,!1),u!==n&&rf(m,u)),z&&(m=Yf(m)));r=m;n=Eg(e,14);m=c.l;m.h=Math.min(3E5,m.h*2);m.i=Math.min(3E5,m.h+Math.round((Math.random()-.5)*.2*
m.h));c.h.setInterval(c.l.getValue());k===401&&f&&(c.da=f);n&&(c.m+=n);l===void 0&&(l=c.isRetryable(k));l&&(c.j=r.concat(c.j),c.Ib||c.h.enabled||c.h.start());b&&b("net-send-failed",k);++c.P};
c.network&&c.network.send(d,g,h)}}}};
p.uc=function(){Zh(this.i,!0);this.flush();Zh(this.i,!1)};
p.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function Uh(){return"https://play.google.com/log?format=json&hasfast=true"}
function Th(a,b){this.eb=b=b===void 0?!1:b;this.i=this.locale=null;this.h=new Nh;Number.isInteger(a)&&this.h.Qb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Vh(this,new Kh)}
Th.prototype.Qb=function(a){this.h.Qb(a);return this};
function Vh(a,b){Cg(a.h,Kh,1,b);Gg(b)||Ig(b,1,1);if(!a.eb){b=$h(a);var c=c===void 0?"":c;var d=ng(b,5);d=d==null||typeof d==="string"?d:void 0;(d!=null?d:c)||Hg(b,5,a.locale)}a.i&&(c=$h(a),Bg(c,Eh,9)||Cg(c,Eh,9,a.i))}
function Xh(a,b){rg(ai(a))&&(a=bi(a),Ig(a,1,b))}
function Zh(a,b){rg(ai(a))&&(a=bi(a),K(a,2,Hf(b)))}
function ai(a){return Bg(a.h,Kh,1)}
function ci(a){var b=b===void 0?Gh:b;var c=a.eb?void 0:window;c?Jh(c,b).then(function(d){a.i=d;d=$h(a);Cg(d,Eh,9,a.i);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function $h(a){a=ai(a);var b=Bg(a,tg,11);b||(b=new tg,Cg(a,tg,11,b));return b}
function bi(a){a=$h(a);var b=Bg(a,Ch,10);b||(b=new Ch,K(b,2,Hf(!1)),Cg(a,Ch,10,b));return b}
function Yh(a,b,c,d,e){var f=0,g=0;c=c===void 0?0:c;f=f===void 0?0:f;g=g===void 0?0:g;d=d===void 0?0:d;if(rg(ai(a))){var h=bi(a);K(h,3,Lf(d))}rg(ai(a))&&(d=bi(a),K(d,4,Lf(f)));rg(ai(a))&&(f=bi(a),K(f,5,Lf(g)));a=a.h.clone();g=Date.now().toString();a=K(a,4,Nf(g));b=b.slice();b=Dg(a,Mh,3,b);e&&(a=new zh,e=K(a,13,Lf(e)),a=new Ah,e=Cg(a,zh,2,e),a=new Lh,e=Cg(a,Ah,1,e),e=Ig(e,2,9),Cg(b,Lh,18,e));c&&K(b,14,Nf(c));return b}
;function di(){this.Gd=typeof AbortController!=="undefined"}
di.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,n,m,r,t;return A(function(v){switch(v.h){case 1:return f=(e=d.Gd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,Aa(v,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.pd)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),v.yield(fetch(a.url,g),5);case 5:h=v.i;if(h.status!==200){(k=c)==null||k(h.status);v.B(3);break}if((l=b)==null){v.B(7);break}return v.yield(h.text(),8);case 8:l(v.i);case 7:case 3:v.P=[v.j];v.l=0;v.v=0;clearTimeout(f);Ca(v);break;case 2:n=Ba(v);switch((m=n)==null?void 0:m.name){case "AbortError":(r=c)==null||r(408);break;default:(t=c)==null||t(400)}v.B(3)}})};
di.prototype.dc=function(){return 4};function ei(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.j="https://play.google.com/log?format=json&hasfast=true";this.h=null;this.l=!1;this.network=null;this.componentId="";this.pageId=this.i=this.zb=null}
y(ei,G);ei.prototype.Vc=function(){this.m=!0;return this};
function fi(a){a.network||(a.network=new di);var b=new Sh({logSource:a.logSource,Kb:a.Kb?a.Kb:wh,sessionIndex:a.sessionIndex,ef:a.j,eb:a.l,Ib:!1,Vc:a.m,Pc:a.Pc,network:a.network});Ec(a,b);if(a.h){var c=a.h,d=$h(b.i);Hg(d,7,c)}a.componentId&&(b.componentId=a.componentId);a.zb&&(b.zb=a.zb);a.pageId&&(b.pageId=a.pageId);a.i&&((d=a.i)?(b.experimentIds||(b.experimentIds=new xh),c=b.experimentIds,d=d.serialize(),Hg(c,4,d)):b.experimentIds&&K(b.experimentIds,4));ci(b.i);a.network.Qb&&a.network.Qb(a.logSource);
a.network.Re&&a.network.Re(b);return b}
;function gi(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;G.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new ei(a,"0"),a.componentId=b,Ec(this,a),c!==""&&(a.j=c),d&&(a.l=!0),e&&(a.h=e),g&&(a.network=g),b=fi(a));this.h=b}
y(gi,G);
gi.prototype.flush=function(a){var b=a||[];if(b.length){a=new kh;for(var c=[],d=0;d<b.length;d++){var e=b[d];var f=new jh;f=Hg(f,1,e.l);for(var g=[],h=0;h<e.fields.length;h++)g.push(e.fields[h].F);f=vg(f,g,Sf);g=[];h=[];for(var k=x(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var n=e.j;for(var m=e.vc(l)||[],r=[],t=0;t<m.length;t++){var v=m[t],u=v&&v.h;v=new gh;switch(n){case 3:u=Number(u);Number.isFinite(u)&&yg(v,1,hh,Nf(u));break;case 2:u=Number(u);
if(u!=null&&typeof u!=="number")throw Error("Value of float/double field must be a number, found "+typeof u+": "+u);yg(v,2,hh,u)}r.push(v)}n=r;for(m=0;m<n.length;m++){r=n[m];t=new ih;r=Cg(t,gh,2,r);t=l;v=[];u=[];for(var z=0;z<e.fields.length;z++)u.push(e.fields[z].G);for(z=0;z<u.length;z++){var F=u[z],I=t[z],O=new eh;switch(F){case 3:yg(O,1,fh,Tf(String(I)));break;case 2:F=Number(I);Number.isFinite(F)&&yg(O,2,fh,Lf(F));break;case 1:yg(O,3,fh,Hf(I==="true"))}v.push(O)}Dg(r,eh,1,v);g.push(r)}}Dg(f,
ih,4,g);c.push(f);e.clear()}Dg(a,jh,1,c);b=this.h;b.H&&(a instanceof Mh?b.log(a):(c=new Mh,a=a.serialize(),a=Hg(c,8,a),b.log(a)));this.h.flush()}};function hi(){}
hi.prototype.serialize=function(a){var b=[];ii(this,a,b);return b.join("")};
function ii(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),ii(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),ji(d,c),c.push(":"),ii(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":ji(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var ki={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},li=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function ji(a,b){b.push('"',a.replace(li,function(c){var d=ki[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),ki[c]=d);return d}),'"')}
;function mi(){}
mi.prototype.h=null;mi.prototype.getOptions=function(){var a;(a=this.h)||(a=this.h={});return a};var ni;function oi(){}
$a(oi,mi);ni=new oi;function pi(a){yd.call(this);this.headers=new Map;this.Ga=a||null;this.i=!1;this.P=this.T=null;this.l=this.da="";this.j=this.ba=this.m=this.W=!1;this.H=0;this.A=null;this.xa="";this.ia=!1}
$a(pi,yd);var qi=/^https?$/i,ri=["POST","PUT"],si=[];function ti(a,b,c,d,e,f,g){var h=new pi;si.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Md,!0,void 0,void 0);f&&(h.H=Math.max(0,f));g&&(h.ia=g);h.send(a,c,d,e)}
p=pi.prototype;p.Md=function(){this.dispose();Ib(si,this)};
p.send=function(a,b,c,d){if(this.T)throw Error("[goog.net.XhrIo] Object is active with another request="+this.da+"; newUri="+a);b=b?b.toUpperCase():"GET";this.da=a;this.l="";this.W=!1;this.i=!0;this.T=new XMLHttpRequest;this.P=this.Ga?this.Ga.getOptions():ni.getOptions();this.T.onreadystatechange=Xa(this.jd,this);try{this.getStatus(),this.ba=!0,this.T.open(b,String(a),!0),this.ba=!1}catch(g){this.getStatus();ui(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if(typeof d.keys==="function"&&typeof d.get==="function"){e=x(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(Cb(ri,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=x(c);for(d=b.next();!d.done;d=b.next())c=x(d.value),d=c.next().value,c=c.next().value,this.T.setRequestHeader(d,c);this.xa&&(this.T.responseType=this.xa);"withCredentials"in this.T&&this.T.withCredentials!==this.ia&&(this.T.withCredentials=this.ia);try{vi(this),this.H>0&&(this.getStatus(),this.A=ne(this.bf,this.H,this)),this.getStatus(),this.m=!0,this.T.send(a),this.m=
!1}catch(g){this.getStatus(),ui(this,g)}};
p.bf=function(){typeof Na!="undefined"&&this.T&&(this.l="Timed out after "+this.H+"ms, aborting",this.getStatus(),zd(this,"timeout"),this.abort(8))};
function ui(a,b){a.i=!1;a.T&&(a.j=!0,a.T.abort(),a.j=!1);a.l=b;wi(a);xi(a)}
function wi(a){a.W||(a.W=!0,zd(a,"complete"),zd(a,"error"))}
p.abort=function(){this.T&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.T.abort(),this.j=!1,zd(this,"complete"),zd(this,"abort"),xi(this))};
p.U=function(){this.T&&(this.i&&(this.i=!1,this.j=!0,this.T.abort(),this.j=!1),xi(this,!0));pi.Ba.U.call(this)};
p.jd=function(){this.V||(this.ba||this.m||this.j?yi(this):this.te())};
p.te=function(){yi(this)};
function yi(a){if(a.i&&typeof Na!="undefined")if(a.P[1]&&zi(a)==4&&a.getStatus()==2)a.getStatus();else if(a.m&&zi(a)==4)ne(a.jd,0,a);else if(zd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(Ai(a))zd(a,"complete"),zd(a,"success");else{try{var b=zi(a)>2?a.T.statusText:""}catch(c){b=""}a.l=b+" ["+a.getStatus()+"]";wi(a)}}finally{xi(a)}}}
function xi(a,b){if(a.T){vi(a);var c=a.T,d=a.P[0]?function(){}:null;
a.T=null;a.P=null;b||zd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function vi(a){a.A&&(C.clearTimeout(a.A),a.A=null)}
p.isActive=function(){return!!this.T};
p.isComplete=function(){return zi(this)==4};
function Ai(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=nc(1,String(a.da)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!qi.test(a?a.toLowerCase():"");c=b}return c}
function zi(a){return a.T?a.T.readyState:0}
p.getStatus=function(){try{return zi(this)>2?this.T.status:-1}catch(a){return-1}};
p.getLastError=function(){return typeof this.l==="string"?this.l:String(this.l)};function Bi(){}
Bi.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
ti(a.url,function(d){d=d.target;if(Ai(d)){try{var e=d.T?d.T.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.pd,a.timeoutMillis,a.withCredentials)};
Bi.prototype.dc=function(){return 1};function Ci(a,b,c){this.logger=a;this.event=b;if(c===void 0||c)this.h=Di()}
Ci.prototype.start=function(){this.h=Di()};
Ci.prototype.done=function(){this.h!=null&&this.logger.ub(this.event,Di()-this.h)};
function Ei(){}
p=Ei.prototype;p.zc=function(){};
p.ub=function(){};
p.ed=function(a,b){a=a();this.ub(b,0);return a};
p.Ha=function(){};
p.Aa=function(){};
function Fi(a,b,c,d){c=c===void 0?"":c;G.call(this);this.Ea=b;this.A=c;this.i=new Map;this.j=new Map;b=new ei(1828,"0");b.h="22";b.network=new Bi;d&&(c=new $g,d=vg(c,d,Kf),b.i=d);this.m=new gi(1828,"","",!1,"",fi(b));this.h=new oe(this.m);this.h.l=1E5;d=this.h;d.flushInterval=3E4;d.h.setInterval(3E4);this.da=new ue(this.h);this.ga=new xe(this.h);this.ia=new ye(this.h);this.ba=new te(this.h);this.H=new ve(this.h);this.P=new we(this.h);this.errorCount=new Be(this.h);this.W=new Ae(this.h);new ze(this.h);
new Ce(this.h);new De(this.h);new Ee(this.h);this.l=a?bh(a):"";a=new se(this.h);this.i.set("h",1);this.i.set("u",2);this.i.set("k",3);this.i.set("P",4);this.i.set("p",5);this.j.set(25,1);this.j.set(26,2);this.j.set(27,3);this.j.set(28,4);a.h.Bb("/client_streamz/bg/fic",this.Ea);Ec(this,this.m);Ec(this,this.h)}
y(Fi,G);p=Fi.prototype;p.zc=function(){this.ga.h.Bb("/client_streamz/bg/fsc",this.l,this.Ea)};
p.ub=function(a,b){if(a==="t")this.da.record(b,this.l,this.Ea);else if(a==="n")this.ia.record(b,this.l,this.Ea);else if(a==="h"||a==="u"||a==="k"||a==="P"||a==="p"){if(a=this.i.get(a))this.H.h.Bb("/client_streamz/bg/fcc",a,this.Ea),this.P.record(b,a,this.Ea)}else this.W.record(b,a,"",this.A,this.Ea)};
p.ed=function(a,b){var c=Di();a=a();this.ub(b,Di()-c);return a};
p.Ha=function(a){var b=this.j.get(a);b?this.ba.h.Bb("/client_streamz/bg/fiec",this.l,this.Ea,b):this.errorCount.h.Bb("/client_streamz/bg/cec",a,"",this.A,this.Ea)};
p.Aa=function(){this.h.Aa()};
function Di(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function Gi(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Hi(a){function b(m,r,t){Promise.resolve().then(function(){l.done();d.ea.Aa();k.resolve({Jd:m,Ue:r,Lg:t})})}
function c(m,r,t,v){var u="k";r?u="h":t&&(u="u");u!=="k"?v!==0&&d.ea.ub(u,m):d.h<=0?(d.ea.ub(u,m),d.h=Math.floor(Math.random()*200)):d.h--}
G.call(this);var d=this;this.h=Math.floor(Math.random()*200);var e=a.program;var f=a.ae;var g=new G;this.addOnDisposeCallback(function(){d.i.then(function(m){m=m.Ue;d.ea.Aa();m==null||m();g.dispose()})});
if(a.Ae!==!1)if(a.ea)this.ea=a.ea;else{var h;Ec(g,this.ea=new Fi(f,(h=a.Ea)!=null?h:"_"))}else this.ea=new Ei;var k=new Gi;this.i=k.promise;var l=new Ci(this.ea,"t",!1);if(!C[f])throw this.ea.Ha(25),this.ea.Aa(),Error("EGOU");if(!C[f].a)throw this.ea.Ha(26),this.ea.Aa(),Error("ELIU");try{var n=C[f].a;l.start();this.j=x(n(e,b,!0,a.Vg,c)).next().value;this.Te=k.promise.then(function(){})}catch(m){throw this.ea.Ha(28),this.ea.Aa(),m;
}}
y(Hi,G);Hi.prototype.snapshot=function(a){var b=this;if(this.V)throw Error("Already disposed");this.ea.zc();return this.i.then(function(c){var d=c.Jd;return new Promise(function(e){var f=new Ci(b.ea,"n");d(function(g){f.done();b.ea.Aa();e(g)},[a.Uc,
a.Ve,a.gf,a.We])})})};
Hi.prototype.vd=function(a){var b=this;if(this.V)throw Error("Already disposed");this.ea.zc();var c=this.ea.ed(function(){return b.j([a.Uc,a.Ve,a.gf,a.We])},"n");
this.ea.Aa();return c};var Ii=window;ib("csi.gstatic.com");ib("googleads.g.doubleclick.net");ib("partner.googleadservices.com");ib("pubads.g.doubleclick.net");ib("securepubads.g.doubleclick.net");ib("tpc.googlesyndication.com");function Ji(a){var b=Ki;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Li(){var a=[];Ji(function(b){a.push(b)});
return a}
var Ki={hf:"allow-forms",jf:"allow-modals",kf:"allow-orientation-lock",lf:"allow-pointer-lock",mf:"allow-popups",nf:"allow-popups-to-escape-sandbox",pf:"allow-presentation",qf:"allow-same-origin",rf:"allow-scripts",sf:"allow-top-navigation",tf:"allow-top-navigation-by-user-activation"},Mi=Ed(function(){return Li()});
function Ni(){var a=Oi(),b={};Db(Mi(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Oi(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Pi(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Qi=(new Date).getTime();function Ri(){var a=Si;return Zg(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
;function Ti(a){yd.call(this);var b=this;this.A=this.j=0;this.Da=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.l=function(){return A(function(e){return e.yield(Ui(b),0)})};
window.addEventListener("offline",this.l);window.addEventListener("online",this.l);this.A||Vi(this)}
y(Ti,yd);function Wi(){var a=Xi;Ti.h||(Ti.h=new Ti(a));return Ti.h}
Ti.prototype.dispose=function(){window.removeEventListener("offline",this.l);window.removeEventListener("online",this.l);this.Da.qa(this.A);delete Ti.h};
Ti.prototype.va=function(){return this.i};
function Vi(a){a.A=a.Da.pa(function(){var b;return A(function(c){if(c.h==1)return a.i?((b=window.navigator)==null?0:b.onLine)?c.B(3):c.yield(Ui(a),3):c.yield(Ui(a),3);Vi(a);c.h=0})},3E4)}
function Ui(a,b){return a.m?a.m:a.m=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,Aa(h,2,3),d&&(a.j=a.Da.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.l=0;h.v=0;a.m=void 0;a.j&&(a.Da.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?zd(a,"networkstatus-online"):zd(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Ba(h),g=!1,h.B(3)}})})}
;function Yi(){this.data=[];this.h=-1}
Yi.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Yi.prototype.get=function(a){return!!this.data[a]};
function Zi(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function $i(){this.blockSize=-1}
;function aj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.v=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
$a(aj,$i);aj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function bj(a,b,c){c||(c=0);var d=a.m;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;e<80;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;e<80;e++){if(e<40)if(e<20){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else e<60?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
aj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.v,f=this.i;d<b;){if(f==0)for(;d<=c;)bj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){bj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){bj(this,e);f=0;break}}this.i=f;this.l+=b}};
aj.prototype.digest=function(){var a=[],b=this.l*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.v[c]=b&255,b/=256;bj(this,this.v);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function cj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function dj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function ej(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:cj(a).match(/\S+/g)||[],b=Cb(a,b)>=0);return b}
function fj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):ej(a,"inverted-hdpi")&&dj(a,Array.prototype.filter.call(a.classList?a.classList:cj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function gj(){}
gj.prototype.next=function(){return hj};
var hj={done:!0,value:void 0};gj.prototype.mb=function(){return this};function ij(a){if(a instanceof jj||a instanceof kj||a instanceof lj)return a;if(typeof a.next=="function")return new jj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new jj(function(){return a[Symbol.iterator]()});
if(typeof a.mb=="function")return new jj(function(){return a.mb()});
throw Error("Not an iterator or iterable.");}
function jj(a){this.h=a}
jj.prototype.mb=function(){return new kj(this.h())};
jj.prototype[Symbol.iterator]=function(){return new lj(this.h())};
jj.prototype.i=function(){return new lj(this.h())};
function kj(a){this.h=a}
y(kj,gj);kj.prototype.next=function(){return this.h.next()};
kj.prototype[Symbol.iterator]=function(){return new lj(this.h)};
kj.prototype.i=function(){return new lj(this.h)};
function lj(a){jj.call(this,function(){return a});
this.j=a}
y(lj,jj);lj.prototype.next=function(){return this.j.next()};function M(a){G.call(this);this.m=1;this.j=[];this.l=0;this.h=[];this.i={};this.A=!!a}
$a(M,G);p=M.prototype;p.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.m;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.m=e+3;d.push(e);return e};
p.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Cb(a)}return!1};
p.Cb=function(a){var b=this.h[a];if(b){var c=this.i[b];this.l!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Ib(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
p.Ya=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];mj(this.h[g+1],this.h[g+2],d)}else{this.l++;try{for(e=0,f=c.length;e<f&&!this.V;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.l--,this.j.length>0&&this.l==0)for(;c=this.j.pop();)this.Cb(c)}}return e!=0}return!1};
function mj(a,b,c){Td(function(){a.apply(b,c)})}
p.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Cb,this),delete this.i[a])}else this.h.length=0,this.i={}};
p.U=function(){M.Ba.U.call(this);this.clear();this.j.length=0};function nj(a){this.h=a}
nj.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new hi).serialize(b))};
nj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
nj.prototype.remove=function(a){this.h.remove(a)};function oj(a){this.h=a}
$a(oj,nj);function pj(a){this.data=a}
function qj(a){return a===void 0||a instanceof pj?a:new pj(a)}
oj.prototype.set=function(a,b){oj.Ba.set.call(this,a,qj(b))};
oj.prototype.i=function(a){a=oj.Ba.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
oj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function rj(a){this.h=a}
$a(rj,oj);rj.prototype.set=function(a,b,c){if(b=qj(b)){if(c){if(c<Za()){rj.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Za()}rj.Ba.set.call(this,a,b)};
rj.prototype.i=function(a){var b=rj.Ba.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Za()||c&&c>Za())rj.prototype.remove.call(this,a);else return b}};function sj(){}
;function tj(){}
$a(tj,sj);tj.prototype[Symbol.iterator]=function(){return ij(this.mb(!0)).i()};
tj.prototype.clear=function(){var a=Array.from(this);a=x(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function uj(a){this.h=a;this.i=null}
$a(uj,tj);p=uj.prototype;p.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
p.set=function(a,b){vj(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
p.get=function(a){vj(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
p.remove=function(a){vj(this);this.h.removeItem(a)};
p.mb=function(a){vj(this);var b=0,c=this.h,d=new gj;d.next=function(){if(b>=c.length)return hj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
p.clear=function(){vj(this);this.h.clear()};
p.key=function(a){vj(this);return this.h.key(a)};
function vj(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Md(Error("Storage mechanism: Storage unavailable"))}
;function wj(){var a=null;try{a=C.localStorage||null}catch(b){}uj.call(this,a)}
$a(wj,uj);function xj(a,b){this.i=a;this.h=b+"::"}
$a(xj,tj);xj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
xj.prototype.get=function(a){return this.i.get(this.h+a)};
xj.prototype.remove=function(a){this.i.remove(this.h+a)};
xj.prototype.mb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new gj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
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
var N={},yj=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";N.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
N.Kc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var zj={nb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
Xc:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},Aj={nb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
Xc:function(a){return[].concat.apply([],a)}};
N.Se=function(){yj?(N.lb=Uint8Array,N.Ja=Uint16Array,N.Ed=Int32Array,N.assign(N,zj)):(N.lb=Array,N.Ja=Array,N.Ed=Array,N.assign(N,Aj))};
N.Se();var Bj=!0;try{new Uint8Array(1)}catch(a){Bj=!1}
function Cj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new N.lb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Dj={};Dj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var Ej={},Fj,Gj=[],Hj=0;Hj<256;Hj++){Fj=Hj;for(var Ij=0;Ij<8;Ij++)Fj=Fj&1?3988292384^Fj>>>1:Fj>>>1;Gj[Hj]=Fj}Ej=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Gj[(a^b[d])&255];return a^-1};var Jj={};Jj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function Kj(a){for(var b=a.length;--b>=0;)a[b]=0}
var Lj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Mj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Nj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Oj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Pj=Array(576);Kj(Pj);var Qj=Array(60);Kj(Qj);var Rj=Array(512);Kj(Rj);var Sj=Array(256);Kj(Sj);var Tj=Array(29);Kj(Tj);var Uj=Array(30);Kj(Uj);function Vj(a,b,c,d,e){this.wd=a;this.Vd=b;this.Ud=c;this.Pd=d;this.qe=e;this.bd=a&&a.length}
var Wj,Xj,Yj;function Zj(a,b){this.Wc=a;this.wb=0;this.Wa=b}
function ak(a,b){a.Z[a.pending++]=b&255;a.Z[a.pending++]=b>>>8&255}
function bk(a,b,c){a.ja>16-c?(a.oa|=b<<a.ja&65535,ak(a,a.oa),a.oa=b>>16-a.ja,a.ja+=c-16):(a.oa|=b<<a.ja&65535,a.ja+=c)}
function ck(a,b,c){bk(a,c[b*2],c[b*2+1])}
function dk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function ek(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=dk(d[e]++,e))}
function fk(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.bb[b*2]=0;for(b=0;b<19;b++)a.ka[b*2]=0;a.ra[512]=1;a.Pa=a.Ab=0;a.ya=a.matches=0}
function gk(a){a.ja>8?ak(a,a.oa):a.ja>0&&(a.Z[a.pending++]=a.oa);a.oa=0;a.ja=0}
function hk(a,b,c){gk(a);ak(a,c);ak(a,~c);N.nb(a.Z,a.window,b,c,a.pending);a.pending+=c}
function ik(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function jk(a,b,c){for(var d=a.aa[c],e=c<<1;e<=a.Na;){e<a.Na&&ik(b,a.aa[e+1],a.aa[e],a.depth)&&e++;if(ik(b,d,a.aa[e],a.depth))break;a.aa[c]=a.aa[e];c=e;e<<=1}a.aa[c]=d}
function kk(a,b,c){var d=0;if(a.ya!==0){do{var e=a.Z[a.Hb+d*2]<<8|a.Z[a.Hb+d*2+1];var f=a.Z[a.yc+d];d++;if(e===0)ck(a,f,b);else{var g=Sj[f];ck(a,g+256+1,b);var h=Lj[g];h!==0&&(f-=Tj[g],bk(a,f,h));e--;g=e<256?Rj[e]:Rj[256+(e>>>7)];ck(a,g,c);h=Mj[g];h!==0&&(e-=Uj[g],bk(a,e,h))}}while(d<a.ya)}ck(a,256,b)}
function lk(a,b){var c=b.Wc,d=b.Wa.wd,e=b.Wa.bd,f=b.Wa.Pd,g,h=-1;a.Na=0;a.qb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.aa[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.aa[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Pa--;e&&(a.Ab-=d[k*2+1])}b.wb=h;for(g=a.Na>>1;g>=1;g--)jk(a,c,g);k=f;do g=a.aa[1],a.aa[1]=a.aa[a.Na--],jk(a,c,1),d=a.aa[1],a.aa[--a.qb]=g,a.aa[--a.qb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.aa[1]=k++,jk(a,c,1);while(a.Na>=
2);a.aa[--a.qb]=a.aa[1];g=b.Wc;k=b.wb;d=b.Wa.wd;e=b.Wa.bd;f=b.Wa.Vd;var l=b.Wa.Ud,n=b.Wa.qe,m,r=0;for(m=0;m<=15;m++)a.Ka[m]=0;g[a.aa[a.qb]*2+1]=0;for(b=a.qb+1;b<573;b++){var t=a.aa[b];m=g[g[t*2+1]*2+1]+1;m>n&&(m=n,r++);g[t*2+1]=m;if(!(t>k)){a.Ka[m]++;var v=0;t>=l&&(v=f[t-l]);var u=g[t*2];a.Pa+=u*(m+v);e&&(a.Ab+=u*(d[t*2+1]+v))}}if(r!==0){do{for(m=n-1;a.Ka[m]===0;)m--;a.Ka[m]--;a.Ka[m+1]+=2;a.Ka[n]--;r-=2}while(r>0);for(m=n;m!==0;m--)for(t=a.Ka[m];t!==0;)d=a.aa[--b],d>k||(g[d*2+1]!==m&&(a.Pa+=(m-g[d*
2+1])*g[d*2],g[d*2+1]=m),t--)}ek(c,h,a.Ka)}
function mk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ka[l*2]+=g:l!==0?(l!==e&&a.ka[l*2]++,a.ka[32]++):g<=10?a.ka[34]++:a.ka[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function nk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do ck(a,l,a.ka);while(--g!==0)}else l!==0?(l!==e&&(ck(a,l,a.ka),g--),ck(a,16,a.ka),bk(a,g-3,2)):g<=10?(ck(a,17,a.ka),bk(a,g-3,3)):(ck(a,18,a.ka),bk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function ok(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var pk=!1;function qk(a,b,c){a.Z[a.Hb+a.ya*2]=b>>>8&255;a.Z[a.Hb+a.ya*2+1]=b&255;a.Z[a.yc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Sj[c]+256+1)*2]++,a.bb[(b<256?Rj[b]:Rj[256+(b>>>7)])*2]++);return a.ya===a.Mb-1}
;function rk(a,b){a.msg=Jj[b];return b}
function sk(a){for(var b=a.length;--b>=0;)a[b]=0}
function tk(a){var b=a.state,c=b.pending;c>a.R&&(c=a.R);c!==0&&(N.nb(a.output,b.Z,b.Ob,c,a.xb),a.xb+=c,b.Ob+=c,a.Lc+=c,a.R-=c,b.pending-=c,b.pending===0&&(b.Ob=0))}
function uk(a,b){var c=a.ta>=0?a.ta:-1,d=a.o-a.ta,e=0;if(a.level>0){a.K.sc===2&&(a.K.sc=ok(a));lk(a,a.hc);lk(a,a.ac);mk(a,a.ra,a.hc.wb);mk(a,a.bb,a.ac.wb);lk(a,a.Qc);for(e=18;e>=3&&a.ka[Oj[e]*2+1]===0;e--);a.Pa+=3*(e+1)+14;var f=a.Pa+3+7>>>3;var g=a.Ab+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)bk(a,b?1:0,3),hk(a,c,d);else if(a.strategy===4||g===f)bk(a,2+(b?1:0),3),kk(a,Pj,Qj);else{bk(a,4+(b?1:0),3);c=a.hc.wb+1;d=a.ac.wb+1;e+=1;bk(a,c-257,5);bk(a,d-1,5);bk(a,e-4,4);for(f=0;f<e;f++)bk(a,a.ka[Oj[f]*
2+1],3);nk(a,a.ra,c-1);nk(a,a.bb,d-1);kk(a,a.ra,a.bb)}fk(a);b&&gk(a);a.ta=a.o;tk(a.K)}
function R(a,b){a.Z[a.pending++]=b}
function vk(a,b){a.Z[a.pending++]=b>>>8&255;a.Z[a.pending++]=b&255}
function wk(a,b){var c=a.gd,d=a.o,e=a.wa,f=a.hd,g=a.o>a.ma-262?a.o-(a.ma-262):0,h=a.window,k=a.Xa,l=a.Ia,n=a.o+258,m=h[d+e-1],r=h[d+e];a.wa>=a.Zc&&(c>>=2);f>a.u&&(f=a.u);do{var t=b;if(h[t+e]===r&&h[t+e-1]===m&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<n;);t=258-(n-d);d=n-258;if(t>e){a.vb=b;e=t;if(t>=f)break;m=h[d+e-1];r=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.u?e:a.u}
function xk(a){var b=a.ma,c;do{var d=a.Cd-a.u-a.o;if(a.o>=b+(b-262)){N.nb(a.window,a.window,b,b,0);a.vb-=b;a.o-=b;a.ta-=b;var e=c=a.fc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.K.na===0)break;e=a.K;c=a.window;f=a.o+a.u;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,N.nb(c,e.input,e.hb,g,f),e.state.wrap===1?e.J=Dj(e.J,c,g,f):e.state.wrap===2&&(e.J=Ej(e.J,c,g,f)),e.hb+=g,e.kb+=g,c=g);a.u+=c;if(a.u+a.sa>=3)for(d=a.o-a.sa,a.M=a.window[d],
a.M=(a.M<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.M=(a.M<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.Xa]=a.head[a.M],a.head[a.M]=d,d++,a.sa--,a.u+a.sa<3););}while(a.u<262&&a.K.na!==0)}
function yk(a,b){for(var c;;){if(a.u<262){xk(a);if(a.u<262&&b===0)return 1;if(a.u===0)break}c=0;a.u>=3&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);c!==0&&a.o-c<=a.ma-262&&(a.S=wk(a,c));if(a.S>=3)if(c=qk(a,a.o-a.vb,a.S-3),a.u-=a.S,a.S<=a.Ac&&a.u>=3){a.S--;do a.o++,a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o;while(--a.S!==0);a.o++}else a.o+=a.S,a.S=0,a.M=a.window[a.o],a.M=(a.M<<a.Ma^a.window[a.o+1])&a.La;else c=qk(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(uk(a,!1),a.K.R===0))return 1}a.sa=a.o<2?a.o:2;return b===4?(uk(a,!0),a.K.R===0?3:4):a.ya&&(uk(a,!1),a.K.R===0)?1:2}
function zk(a,b){for(var c,d;;){if(a.u<262){xk(a);if(a.u<262&&b===0)return 1;if(a.u===0)break}c=0;a.u>=3&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);a.wa=a.S;a.ld=a.vb;a.S=2;c!==0&&a.wa<a.Ac&&a.o-c<=a.ma-262&&(a.S=wk(a,c),a.S<=5&&(a.strategy===1||a.S===3&&a.o-a.vb>4096)&&(a.S=2));if(a.wa>=3&&a.S<=a.wa){d=a.o+a.u-3;c=qk(a,a.o-1-a.ld,a.wa-3);a.u-=a.wa-1;a.wa-=2;do++a.o<=d&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);
while(--a.wa!==0);a.fb=0;a.S=2;a.o++;if(c&&(uk(a,!1),a.K.R===0))return 1}else if(a.fb){if((c=qk(a,0,a.window[a.o-1]))&&uk(a,!1),a.o++,a.u--,a.K.R===0)return 1}else a.fb=1,a.o++,a.u--}a.fb&&(qk(a,0,a.window[a.o-1]),a.fb=0);a.sa=a.o<2?a.o:2;return b===4?(uk(a,!0),a.K.R===0?3:4):a.ya&&(uk(a,!1),a.K.R===0)?1:2}
function Ak(a,b){for(var c,d,e,f=a.window;;){if(a.u<=258){xk(a);if(a.u<=258&&b===0)return 1;if(a.u===0)break}a.S=0;if(a.u>=3&&a.o>0&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.S=258-(e-d);a.S>a.u&&(a.S=a.u)}a.S>=3?(c=qk(a,1,a.S-3),a.u-=a.S,a.o+=a.S,a.S=0):(c=qk(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(uk(a,!1),a.K.R===0))return 1}a.sa=0;return b===4?(uk(a,!0),a.K.R===0?3:4):
a.ya&&(uk(a,!1),a.K.R===0)?1:2}
function Bk(a,b){for(var c;;){if(a.u===0&&(xk(a),a.u===0)){if(b===0)return 1;break}a.S=0;c=qk(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(uk(a,!1),a.K.R===0))return 1}a.sa=0;return b===4?(uk(a,!0),a.K.R===0?3:4):a.ya&&(uk(a,!1),a.K.R===0)?1:2}
function Ck(a,b,c,d,e){this.be=a;this.pe=b;this.se=c;this.oe=d;this.Xd=e}
var Dk;Dk=[new Ck(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.u<=1){xk(a);if(a.u===0&&b===0)return 1;if(a.u===0)break}a.o+=a.u;a.u=0;var d=a.ta+c;if(a.o===0||a.o>=d)if(a.u=a.o-d,a.o=d,uk(a,!1),a.K.R===0)return 1;if(a.o-a.ta>=a.ma-262&&(uk(a,!1),a.K.R===0))return 1}a.sa=0;if(b===4)return uk(a,!0),a.K.R===0?3:4;a.o>a.ta&&uk(a,!1);return 1}),
new Ck(4,4,8,4,yk),new Ck(4,5,16,8,yk),new Ck(4,6,32,32,yk),new Ck(4,4,16,16,zk),new Ck(8,16,32,32,zk),new Ck(8,16,128,128,zk),new Ck(8,32,128,256,zk),new Ck(32,128,258,1024,zk),new Ck(32,258,258,4096,zk)];
function Ek(){this.K=null;this.status=0;this.Z=null;this.wrap=this.pending=this.Ob=this.za=0;this.I=null;this.Ca=0;this.method=8;this.sb=-1;this.Xa=this.Nc=this.ma=0;this.window=null;this.Cd=0;this.head=this.Ia=null;this.hd=this.Zc=this.strategy=this.level=this.Ac=this.gd=this.wa=this.u=this.vb=this.o=this.fb=this.ld=this.S=this.ta=this.Ma=this.La=this.wc=this.fc=this.M=0;this.ra=new N.Ja(1146);this.bb=new N.Ja(122);this.ka=new N.Ja(78);sk(this.ra);sk(this.bb);sk(this.ka);this.Qc=this.ac=this.hc=
null;this.Ka=new N.Ja(16);this.aa=new N.Ja(573);sk(this.aa);this.qb=this.Na=0;this.depth=new N.Ja(573);sk(this.depth);this.ja=this.oa=this.sa=this.matches=this.Ab=this.Pa=this.Hb=this.ya=this.Mb=this.yc=0}
function Fk(a,b){if(!a||!a.state||b>5||b<0)return a?rk(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return rk(a,a.R===0?-5:-2);c.K=a;var d=c.sb;c.sb=b;if(c.status===42)if(c.wrap===2)a.J=0,R(c,31),R(c,139),R(c,8),c.I?(R(c,(c.I.text?1:0)+(c.I.Ta?2:0)+(c.I.extra?4:0)+(c.I.name?8:0)+(c.I.comment?16:0)),R(c,c.I.time&255),R(c,c.I.time>>8&255),R(c,c.I.time>>16&255),R(c,c.I.time>>24&255),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,c.I.os&255),c.I.extra&&c.I.extra.length&&
(R(c,c.I.extra.length&255),R(c,c.I.extra.length>>8&255)),c.I.Ta&&(a.J=Ej(a.J,c.Z,c.pending,0)),c.Ca=0,c.status=69):(R(c,0),R(c,0),R(c,0),R(c,0),R(c,0),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,3),c.status=113);else{var e=8+(c.Nc-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.o!==0&&(e|=32);c.status=113;vk(c,e+(31-e%31));c.o!==0&&(vk(c,a.J>>>16),vk(c,a.J&65535));a.J=1}if(c.status===69)if(c.I.extra){for(e=c.pending;c.Ca<(c.I.extra.length&65535)&&(c.pending!==c.za||
(c.I.Ta&&c.pending>e&&(a.J=Ej(a.J,c.Z,c.pending-e,e)),tk(a),e=c.pending,c.pending!==c.za));)R(c,c.I.extra[c.Ca]&255),c.Ca++;c.I.Ta&&c.pending>e&&(a.J=Ej(a.J,c.Z,c.pending-e,e));c.Ca===c.I.extra.length&&(c.Ca=0,c.status=73)}else c.status=73;if(c.status===73)if(c.I.name){e=c.pending;do{if(c.pending===c.za&&(c.I.Ta&&c.pending>e&&(a.J=Ej(a.J,c.Z,c.pending-e,e)),tk(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ca<c.I.name.length?c.I.name.charCodeAt(c.Ca++)&255:0;R(c,f)}while(f!==0);c.I.Ta&&c.pending>
e&&(a.J=Ej(a.J,c.Z,c.pending-e,e));f===0&&(c.Ca=0,c.status=91)}else c.status=91;if(c.status===91)if(c.I.comment){e=c.pending;do{if(c.pending===c.za&&(c.I.Ta&&c.pending>e&&(a.J=Ej(a.J,c.Z,c.pending-e,e)),tk(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ca<c.I.comment.length?c.I.comment.charCodeAt(c.Ca++)&255:0;R(c,f)}while(f!==0);c.I.Ta&&c.pending>e&&(a.J=Ej(a.J,c.Z,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.I.Ta?(c.pending+2>c.za&&tk(a),c.pending+2<=c.za&&(R(c,a.J&
255),R(c,a.J>>8&255),a.J=0,c.status=113)):c.status=113);if(c.pending!==0){if(tk(a),a.R===0)return c.sb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return rk(a,-5);if(c.status===666&&a.na!==0)return rk(a,-5);if(a.na!==0||c.u!==0||b!==0&&c.status!==666){d=c.strategy===2?Bk(c,b):c.strategy===3?Ak(c,b):Dk[c.level].Xd(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.R===0&&(c.sb=-1),0;if(d===2&&(b===1?(bk(c,2,3),ck(c,256,Pj),c.ja===16?(ak(c,c.oa),c.oa=0,c.ja=0):c.ja>=8&&
(c.Z[c.pending++]=c.oa&255,c.oa>>=8,c.ja-=8)):b!==5&&(bk(c,0,3),hk(c,0,0),b===3&&(sk(c.head),c.u===0&&(c.o=0,c.ta=0,c.sa=0))),tk(a),a.R===0))return c.sb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(R(c,a.J&255),R(c,a.J>>8&255),R(c,a.J>>16&255),R(c,a.J>>24&255),R(c,a.kb&255),R(c,a.kb>>8&255),R(c,a.kb>>16&255),R(c,a.kb>>24&255)):(vk(c,a.J>>>16),vk(c,a.J&65535));tk(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var Gk={};Gk=function(){this.input=null;this.kb=this.na=this.hb=0;this.output=null;this.Lc=this.R=this.xb=0;this.msg="";this.state=null;this.sc=2;this.J=0};var Hk=Object.prototype.toString;
function Ik(a){if(!(this instanceof Ik))return new Ik(a);a=this.options=N.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.K=new Gk;this.K.R=0;var b=this.K;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=rk(b,-2);else{e===8&&(e=9);var k=new Ek;b.state=k;k.K=b;k.wrap=h;k.I=null;k.Nc=e;k.ma=1<<k.Nc;k.Xa=k.ma-1;k.wc=f+7;k.fc=1<<k.wc;k.La=k.fc-1;k.Ma=~~((k.wc+3-1)/3);k.window=new N.lb(k.ma*2);k.head=new N.Ja(k.fc);k.Ia=new N.Ja(k.ma);k.Mb=1<<f+6;k.za=k.Mb*4;k.Z=new N.lb(k.za);k.Hb=1*k.Mb;k.yc=3*k.Mb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.kb=b.Lc=0;b.sc=2;c=b.state;c.pending=0;c.Ob=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.J=c.wrap===2?
0:1;c.sb=0;if(!pk){d=Array(16);for(f=g=0;f<28;f++)for(Tj[f]=g,e=0;e<1<<Lj[f];e++)Sj[g++]=f;Sj[g-1]=f;for(f=g=0;f<16;f++)for(Uj[f]=g,e=0;e<1<<Mj[f];e++)Rj[g++]=f;for(g>>=7;f<30;f++)for(Uj[f]=g<<7,e=0;e<1<<Mj[f]-7;e++)Rj[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)Pj[e*2+1]=8,e++,d[8]++;for(;e<=255;)Pj[e*2+1]=9,e++,d[9]++;for(;e<=279;)Pj[e*2+1]=7,e++,d[7]++;for(;e<=287;)Pj[e*2+1]=8,e++,d[8]++;ek(Pj,287,d);for(e=0;e<30;e++)Qj[e*2+1]=5,Qj[e*2]=dk(e,5);Wj=new Vj(Pj,Lj,257,286,15);Xj=new Vj(Qj,
Mj,0,30,15);Yj=new Vj([],Nj,0,19,7);pk=!0}c.hc=new Zj(c.ra,Wj);c.ac=new Zj(c.bb,Xj);c.Qc=new Zj(c.ka,Yj);c.oa=0;c.ja=0;fk(c);c=0}else c=rk(b,-2);c===0&&(b=b.state,b.Cd=2*b.ma,sk(b.head),b.Ac=Dk[b.level].pe,b.Zc=Dk[b.level].be,b.hd=Dk[b.level].se,b.gd=Dk[b.level].oe,b.o=0,b.ta=0,b.u=0,b.sa=0,b.S=b.wa=2,b.fb=0,b.M=0);b=c}}else b=-2;if(b!==0)throw Error(Jj[b]);a.header&&(b=this.K)&&b.state&&b.state.wrap===2&&(b.state.I=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=Cj(a.dictionary):
Hk.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.K;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.u)b=-2;else{b===1&&(a.J=Dj(a.J,f,g,0));l.wrap=0;g>=l.ma&&(b===0&&(sk(l.head),l.o=0,l.ta=0,l.sa=0),c=new N.lb(l.ma),N.nb(c,f,g-l.ma,l.ma,0),f=c,g=l.ma);c=a.na;d=a.hb;e=a.input;a.na=g;a.hb=0;a.input=f;for(xk(l);l.u>=3;){f=l.o;g=l.u-2;do l.M=(l.M<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.Xa]=l.head[l.M],l.head[l.M]=f,f++;while(--g);
l.o=f;l.u=2;xk(l)}l.o+=l.u;l.ta=l.o;l.sa=l.u;l.u=0;l.S=l.wa=2;l.fb=0;a.hb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(Jj[b]);this.wg=!0}}
Ik.prototype.push=function(a,b){var c=this.K,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=Cj(a):Hk.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.hb=0;c.na=c.input.length;do{c.R===0&&(c.output=new N.lb(d),c.xb=0,c.R=d);a=Fk(c,e);if(a!==1&&a!==0)return Jk(this,a),this.ended=!0,!1;if(c.R===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=N.Kc(c.output,c.xb);b=f;f=f.length;if(f<65537&&(b.subarray&&Bj||!b.subarray))b=
String.fromCharCode.apply(null,N.Kc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=N.Kc(c.output,c.xb),this.chunks.push(b)}while((c.na>0||c.R===0)&&a!==1);if(e===4)return(c=this.K)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=rk(c,-2):(c.state=null,a=d===113?rk(c,-3):0)):a=-2,Jk(this,a),this.ended=!0,a===0;e===2&&(Jk(this,0),c.R=0);return!0};
function Jk(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):N.Xc(a.chunks));a.chunks=[];a.err=b;a.msg=a.K.msg}
function Kk(a,b){b=b||{};b.gzip=!0;b=new Ik(b);b.push(a,!0);if(b.err)throw b.msg||Jj[b.err];return b.result}
;function Lk(a){if(!a)return null;a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue;var b;a?b=mb(a):b=null;return b}
;function Mk(a){return mb(a===null?"null":a===void 0?"undefined":a)}
;function Nk(a){this.name=a}
;var Ok=new Nk("rawColdConfigGroup");var Pk=new Nk("rawHotConfigGroup");function Qk(a){this.D=J(a)}
y(Qk,L);var Rk=new Nk("continuationCommand");var Sk=new Nk("webCommandMetadata");var Tk=new Nk("signalServiceEndpoint");var Uk={yf:"EMBEDDED_PLAYER_MODE_UNKNOWN",vf:"EMBEDDED_PLAYER_MODE_DEFAULT",xf:"EMBEDDED_PLAYER_MODE_PFP",wf:"EMBEDDED_PLAYER_MODE_PFL"};var Vk=new Nk("feedbackEndpoint");function Wk(a){this.D=J(a)}
y(Wk,L);Wk.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new Ye(a,Ve):We||(We=new Ye(null,Ve));else if(a.constructor!==Ye)if(Ue(a))a=a.length?new Ye(new Uint8Array(a),Ve):We||(We=new Ye(null,Ve));else throw Error();return K(this,1,a)};var Si={ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",If:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Rf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",Ff:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Uf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Sf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Tf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",Jf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Nf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Mf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Pf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Qf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Of:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Cf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Bf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Df:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Ef:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",Gf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",Hf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Lf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",Kf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED"};var Xk=new Nk("shareEndpoint"),Yk=new Nk("shareEntityEndpoint"),Zk=new Nk("shareEntityServiceEndpoint"),$k=new Nk("webPlayerShareEntityServiceEndpoint");var al=new Nk("playlistEditEndpoint");var bl=new Nk("modifyChannelNotificationPreferenceEndpoint");var cl=new Nk("unsubscribeEndpoint");var dl=new Nk("subscribeEndpoint");function el(){var a=fl;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function gl(a){D("yt.ads.biscotti.lastId_",a)}
;function hl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var il=C.window,jl,kl,ll=(il==null?void 0:(jl=il.yt)==null?void 0:jl.config_)||(il==null?void 0:(kl=il.ytcfg)==null?void 0:kl.data_)||{};D("yt.config_",ll);function ml(){hl(ll,arguments)}
function T(a,b){return a in ll?ll[a]:b}
function nl(a){var b=ll.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var ol=[];function pl(a){ol.forEach(function(b){return b(a)})}
function ql(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){rl(b)}}:a}
function rl(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=T("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),ml("ERRORS",b));pl(a)}
function sl(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=T("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),ml("ERRORS",f))}
;var tl=/^[\w.]*$/,ul={q:!0,search_query:!0};function vl(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=wl(f[0]||""),h=wl(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Jb(k,h):c[g]=[k,h]}else c[g]=h}catch(r){var l=r,n=f[0],m=String(vl);l.args=[{key:n,value:f[1],query:a,method:xl===m?"unchanged":m}];ul.hasOwnProperty(n)||sl(l)}}return c}
var xl=String(vl);function yl(a){var b=[];Kb(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Db(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function zl(a){a.charAt(0)==="?"&&(a=a.substring(1));return vl(a,"&")}
function Al(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),zl(a.length>1?a[1]:a[0])):{}}
function Bl(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=zl(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return tc(a,e)+d}
function Cl(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)===d&&(Number(nc(4,b))||null)===(Number(nc(4,a))||null):!0;return a}
function wl(a){return a&&a.match(tl)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Dl(a){var b=El;a=a===void 0?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Qi;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ka){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?Ii:g;try{var h=g.history.length}catch(Ka){h=0}e.u_his=h;var k;e.u_h=(k=Ii.screen)==null?void 0:k.height;var l;e.u_w=(l=Ii.screen)==null?void 0:l.width;var n;e.u_ah=(n=Ii.screen)==null?void 0:n.availHeight;var m;e.u_aw=
(m=Ii.screen)==null?void 0:m.availWidth;var r;e.u_cd=(r=Ii.screen)==null?void 0:r.colorDepth}catch(Ka){}h=b.h;try{var t=h.screenX;var v=h.screenY}catch(Ka){}try{var u=h.outerWidth;var z=h.outerHeight}catch(Ka){}try{var F=h.innerWidth;var I=h.innerHeight}catch(Ka){}try{var O=h.screenLeft;var S=h.screenTop}catch(Ka){}try{F=h.innerWidth,I=h.innerHeight}catch(Ka){}try{var da=h.screen.availWidth;var ta=h.screen.availTop}catch(Ka){}t=[O,S,t,v,da,ta,u,z,F,I];try{var P=(b.h.top||window).document,ea=P.compatMode==
"CSS1Compat"?P.documentElement:P.body;var na=(new Gd(ea.clientWidth,ea.clientHeight)).round()}catch(Ka){na=new Gd(-12245933,-12245933)}P=na;na={};var La=La===void 0?C:La;ea=new Yi;"SVGElement"in La&&"createElementNS"in La.document&&ea.set(0);v=Ni();v["allow-top-navigation-by-user-activation"]&&ea.set(1);v["allow-popups-to-escape-sandbox"]&&ea.set(2);La.crypto&&La.crypto.subtle&&ea.set(3);"TextDecoder"in La&&"TextEncoder"in La&&ea.set(4);La=Zi(ea);na.bc=La;na.bih=P.height;na.biw=P.width;na.brdim=t.join();
b=b.i;b=(na.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,na.wgl=!!Ii.WebGLRenderingContext,na);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var El=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return yl(Dl(a))});Za();navigator.userAgent.indexOf(" (CrKey ");var Fl="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function Gl(){if(!Fl)return null;var a=Fl();return"open"in a?a:null}
function Hl(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Il(a,b){typeof a==="function"&&(a=ql(a));return window.setTimeout(a,b)}
;var Jl="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(la(Jl),["client_dev_set_cookie"]);function U(a){a=Kl(a);return typeof a==="string"&&a==="false"?!1:!!a}
function Ll(a,b){a=Kl(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function Kl(a){return T("EXPERIMENT_FLAGS",{})[a]}
function Ml(){for(var a=[],b=T("EXPERIMENTS_FORCED_FLAGS",{}),c=x(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=T("EXPERIMENT_FLAGS",{});d=x(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var Nl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Ol="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(la(Jl)),Pl=!1;
function Ql(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&ql(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=Gl();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;U("debug_forward_web_query_parameters")&&(a=Rl(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Sl(a,e))for(var n in e)l.setRequestHeader(n,e[n]),"content-type"===n.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(m){sl(m)}}l.send(d);return l}
function Sl(a,b){b=b===void 0?{}:b;var c=Cl(a),d=T("INNERTUBE_CLIENT_NAME"),e=U("web_ajax_ignore_global_headers_if_set"),f;for(f in Nl){var g=T(Nl[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=T("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(oc(a)?!1:!0))){k=a;var l;if(l=U("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=oc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=mc(nc(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var n=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(m){}n&&
(b["X-YouTube-Time-Zone"]=n)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&oc(a)||(b["X-YouTube-Ad-Signals"]=yl(Dl()));return b}
function Tl(a,b){b.method="POST";b.postParams||(b.postParams={});return Ul(a,b)}
function Ul(a,b){var c=b.format||"JSON";a=Vl(a,b);var d=Wl(a,b),e=!1,f=Xl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=Hl(k),n=null,m=400<=k.status&&k.status<500,r=500<=k.status&&k.status<600;if(l||m||r)n=Yl(a,c,k,b.convertToSafeHtml);l&&(l=Zl(c,k,n));n=n||{};m=b.context||C;l?b.onSuccess&&b.onSuccess.call(m,k,n):b.onError&&b.onError.call(m,k,n);b.onFinish&&b.onFinish.call(m,k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=Il(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function Vl(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=T("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Bl(a,b||{},!0);return a}
function Wl(a,b){var c=T("XSRF_FIELD_NAME"),d=T("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=T("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(U("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=zl(e),Ub(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):sc(e));f=e||f&&!Nb(f);!Pl&&f&&b.method!=="POST"&&(Pl=!0,rl(Error("AJAX request with postData should use POST")));return e}
function Yl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,sl(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?$l(a):null)e={},Db(a.getElementsByTagName("*"),function(g){e[g.tagName]=am(g)})}d&&bm(e);
return e}
function bm(a){if(Ra(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=fb();d=e?e.createHTML(d):d;a[c]=new Vb(d)}else bm(a[b])}}
function Zl(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function $l(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function am(a){var b="";Db(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Rl(a){var b=window.location.search,c=oc(a);U("debug_handle_relative_url_for_query_forward_killswitch")||!c&&Cl(a)&&(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=zl(b),f={};Db(Ol,function(g){e[g]&&(f[g]=e[g])});
return Bl(a,f||{},!1)}
var Xl=Ql;var cm=[{Bc:function(a){return"Cannot read property '"+a.key+"'"},
ic:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Bc:function(a){return"Cannot call '"+a.key+"'"},
ic:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Bc:function(a){return a.key+" is not defined"},
ic:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var em={Va:[],Sa:[{callback:dm,weight:500}]};function dm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function fm(){this.Sa=[];this.Va=[]}
var gm;function hm(){if(!gm){var a=gm=new fm;a.Va.length=0;a.Sa.length=0;em.Va&&a.Va.push.apply(a.Va,em.Va);em.Sa&&a.Sa.push.apply(a.Sa,em.Sa)}return gm}
;var im=new M;function jm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=km(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=km(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=km(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function km(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function lm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=mm(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=jm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?mm(f+".ve",g,h,k):0;d+=f;d+=mm(e,a[e],b,c);if(d>500)break}}else c[b]=nm(a),d+=c[b].length;else c[b]=nm(a),d+=c[b].length;return d}
function mm(a,b,c,d){c+="."+a;a=nm(b);d[c]=a;return c.length+a.length}
function nm(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function om(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function pm(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function qm(){this.Xe=!0}
function rm(){qm.h||(qm.h=new qm);return qm.h}
function sm(a,b){a={};var c=[];"SESSION_ID"in ll&&c.push({key:"u",value:T("SESSION_ID")});if(c=wh(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(T("SESSION_INDEX",0)),c=isNaN(c)?0:c),U("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in ll||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in ll&&(a["X-Goog-PageId"]=T("DELEGATED_SESSION_ID"));return a}
;var tm={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function um(a,b,c,d,e){sh.set(""+a,b,{Nb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function wm(a){return sh.get(""+a,void 0)}
function xm(a,b,c){sh.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function ym(){if(U("embeds_web_enable_cookie_detection_fix")){if(!C.navigator.cookieEnabled)return!1}else if(!sh.isEnabled())return!1;if(sh.h.cookie)return!0;U("embeds_web_enable_cookie_detection_fix")?sh.set("TESTCOOKIESENABLED","1",{Nb:60,Ge:"none",secure:!0}):sh.set("TESTCOOKIESENABLED","1",{Nb:60});if(sh.get("TESTCOOKIESENABLED")!=="1")return!1;sh.remove("TESTCOOKIESENABLED");return!0}
;var zm=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",zm);function Am(){this.h=T("ALT_PREF_COOKIE_NAME","PREF");this.i=T("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=wm(this.h);a&&this.parse(a)}
var Bm;function Cm(){Bm||(Bm=new Am);return Bm}
p=Am.prototype;p.get=function(a,b){Dm(a);Em(a);a=zm[a]!==void 0?zm[a].toString():null;return a!=null?a:b?b:""};
p.set=function(a,b){Dm(a);Em(a);if(b==null)throw Error("ExpectedNotNull");zm[a]=b.toString()};
function Fm(a){return!!((Gm("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
p.remove=function(a){Dm(a);Em(a);delete zm[a]};
p.clear=function(){for(var a in zm)delete zm[a]};
function Em(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Dm(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Gm(a){a=zm[a]!==void 0?zm[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
p.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(zm[d]=c.toString())}};var Hm={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Im={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Jm(){var a=C.navigator;return a?a.connection:void 0}
function Km(){var a=Jm();if(a){var b=Hm[a.type||"unknown"]||"CONN_UNKNOWN";a=Hm[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function Lm(){var a=Jm();if(a!=null&&a.effectiveType)return Im.hasOwnProperty(a.effectiveType)?Im[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function V(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(la(b))}
y(V,Error);function Mm(){try{return Nm(),!0}catch(a){return!1}}
function Nm(a){if(T("DATASYNC_ID")!==void 0)return T("DATASYNC_ID");throw new V("Datasync ID not set",a===void 0?"unknown":a);}
;function Om(){}
function Pm(a,b){return Xi.ab(a,0,b)}
Om.prototype.pa=function(a,b){return this.ab(a,1,b)};
Om.prototype.Eb=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Qm=Ll("web_emulated_idle_callback_delay",300),Rm=1E3/60-3,Sm=[8,5,4,3,2,1,0];
function Tm(a){a=a===void 0?{}:a;G.call(this);this.i=[];this.j={};this.da=this.h=0;this.ba=this.m=!1;this.P=[];this.W=this.ga=!1;for(var b=x(Sm),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.l=0;this.qc=a.timeout||1;this.H=Rm;this.A=0;this.xa=this.ue.bind(this);this.pc=this.af.bind(this);this.Za=this.Id.bind(this);this.Db=this.ce.bind(this);this.Tb=this.ye.bind(this);this.Ga=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!U("disable_scheduler_requestIdleCallback");(this.ia=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
y(Tm,G);p=Tm.prototype;p.Eb=function(a){var b=Za();Um(this,a);a=Za()-b;this.m||(this.H-=a)};
p.ab=function(a,b,c){++this.da;if(b===10)return this.Eb(a),this.da;var d=this.da;this.j[d]=a;this.m&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.ba||this.m||(this.h!==0&&Vm(this)!==this.A&&this.stop(),this.start()));return d};
p.qa=function(a){delete this.j[a]};
function Wm(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
p.isHidden=function(){return!!document.hidden||!1};
function Xm(a){return!a.isHidden()&&a.ia}
function Vm(a){if(a.i[8].length){if(a.W)return 4;if(Xm(a))return 3}for(var b=5;b>=a.l;b--)if(a.i[b].length>0)return b>0?Xm(a)?3:2:1;return 0}
p.Ha=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function Um(a,b){try{b()}catch(c){a.Ha(c)}}
function Ym(a){for(var b=x(Sm),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
p.ce=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ga=!0;Zm(this,b);this.ga=!1};
p.af=function(){Zm(this)};
p.Id=function(){$m(this)};
p.ye=function(a){this.W=!0;var b=Vm(this);b===4&&b!==this.A&&(this.stop(),this.start());Zm(this,void 0,a);this.W=!1};
p.ue=function(){this.isHidden()||$m(this);this.h&&(this.stop(),this.start())};
function $m(a){a.stop();a.m=!0;for(var b=Za(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Um(a,e)}an(a);a.m=!1;Ym(a)&&a.start();b=Za()-b;a.H-=b}
function an(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function Zm(a,b,c){a.W&&a.A===4&&a.h||a.stop();a.m=!0;b=Za()+(b||a.H);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Um(a,f);d=a.ga?0:1;d=a.l>d?a.l:d;if(!(Za()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Um(a,c)}while(c&&Za()<b)}a.m=!1;an(a);a.H=Rm;Ym(a)&&a.start()}
p.start=function(){this.ba=!1;if(this.h===0)switch(this.A=Vm(this),this.A){case 1:var a=this.Db;this.h=this.Ga?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Qm);break;case 2:this.h=window.setTimeout(this.pc,this.qc);break;case 3:this.h=window.requestAnimationFrame(this.Tb);break;case 4:this.h=window.setTimeout(this.Za,0)}};
p.pause=function(){this.stop();this.ba=!0};
p.stop=function(){if(this.h){switch(this.A){case 1:var a=this.h;this.Ga?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
p.U=function(){Wm(this);this.stop();this.ia&&document.removeEventListener("visibilitychange",this.xa);G.prototype.U.call(this)};var bn=E("yt.scheduler.instance.timerIdMap_")||{},cn=Ll("kevlar_tuner_scheduler_soft_state_timer_ms",800),dn=0,en=0;function fn(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.V)a=new Tm(T("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function gn(){hn();var a=E("ytglobal.schedulerInstanceInstance_");a&&(Cc(a),D("ytglobal.schedulerInstanceInstance_",null))}
function hn(){Wm(fn());for(var a in bn)bn.hasOwnProperty(a)&&delete bn[Number(a)]}
function jn(a,b,c){if(!c)return c=c===void 0,-fn().ab(a,b,c);var d=window.setTimeout(function(){var e=fn().ab(a,b);bn[d]=e},c);
return d}
function kn(a){fn().Eb(a)}
function ln(a){var b=fn();if(a<0)b.qa(-a);else{var c=bn[a];c?(b.qa(c),delete bn[a]):window.clearTimeout(a)}}
function mn(){nn()}
function nn(){window.clearTimeout(dn);fn().start()}
function on(){fn().pause();window.clearTimeout(dn);dn=window.setTimeout(mn,cn)}
function pn(){window.clearTimeout(en);en=window.setTimeout(function(){qn(0)},cn)}
function qn(a){pn();var b=fn();b.l=a;b.start()}
function rn(a){pn();var b=fn();b.l>a&&(b.l=a,b.start())}
function sn(){window.clearTimeout(en);var a=fn();a.l=0;a.start()}
;function tn(){Om.apply(this,arguments)}
y(tn,Om);function un(){tn.h||(tn.h=new tn);return tn.h}
tn.prototype.ab=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):Il(a,c||0)};
tn.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
tn.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
tn.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var Xi=un();
U("web_scheduler_auto_init")&&!E("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",gn),D("yt.scheduler.instance.addJob",jn),D("yt.scheduler.instance.addImmediateJob",kn),D("yt.scheduler.instance.cancelJob",ln),D("yt.scheduler.instance.cancelAllJobs",hn),D("yt.scheduler.instance.start",nn),D("yt.scheduler.instance.pause",on),D("yt.scheduler.instance.setPriorityThreshold",qn),D("yt.scheduler.instance.enablePriorityThreshold",rn),D("yt.scheduler.instance.clearPriorityThreshold",sn),D("yt.scheduler.initialized",
!0));function vn(a){var b=new wj;this.h=(a=b.isAvailable()?a?new xj(b,a):b:null)?new rj(a):null;this.i=document.domain||window.location.hostname}
vn.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new hi).serialize(b))}catch(f){return}else e=escape(b);um(a,e,c,this.i)};
vn.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=wm(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
vn.prototype.remove=function(a){this.h&&this.h.remove(a);xm(a,"/",this.i)};var wn=function(){var a;return function(){a||(a=new vn("ytidb"));return a}}();
function xn(){var a;return(a=wn())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var yn=[],zn,An=!1;function Bn(){var a={};for(zn=new Cn(a.handleError===void 0?Dn:a.handleError,a.logEvent===void 0?En:a.logEvent);yn.length>0;)switch(a=yn.shift(),a.type){case "ERROR":zn.Ha(a.payload);break;case "EVENT":zn.logEvent(a.eventType,a.payload)}}
function Fn(a){An||(zn?zn.Ha(a):(yn.push({type:"ERROR",payload:a}),yn.length>10&&yn.shift()))}
function Gn(a,b){An||(zn?zn.logEvent(a,b):(yn.push({type:"EVENT",eventType:a,payload:b}),yn.length>10&&yn.shift()))}
;function Hn(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function In(a){return a.substr(0,a.indexOf(":"))||a}
;var Jn=Fe||Ge;function Kn(a){var b=Lc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var Ln={},Mn=(Ln.AUTH_INVALID="No user identifier specified.",Ln.EXPLICIT_ABORT="Transaction was explicitly aborted.",Ln.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Ln.MISSING_INDEX="Index not created.",Ln.MISSING_OBJECT_STORES="Object stores not created.",Ln.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Ln.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Ln.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Ln.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Ln.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Ln.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Ln.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Ln),Nn={},On=(Nn.AUTH_INVALID="ERROR",Nn.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Nn.EXPLICIT_ABORT="IGNORED",Nn.IDB_NOT_SUPPORTED="ERROR",Nn.MISSING_INDEX=
"WARNING",Nn.MISSING_OBJECT_STORES="ERROR",Nn.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Nn.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Nn.QUOTA_EXCEEDED="WARNING",Nn.QUOTA_MAYBE_EXCEEDED="WARNING",Nn.UNKNOWN_ABORT="WARNING",Nn.INCOMPATIBLE_DB_VERSION="WARNING",Nn),Pn={},Qn=(Pn.AUTH_INVALID=!1,Pn.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Pn.EXPLICIT_ABORT=!1,Pn.IDB_NOT_SUPPORTED=!1,Pn.MISSING_INDEX=!1,Pn.MISSING_OBJECT_STORES=!1,Pn.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Pn.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Pn.QUOTA_EXCEEDED=!1,Pn.QUOTA_MAYBE_EXCEEDED=!0,Pn.UNKNOWN_ABORT=!0,Pn.INCOMPATIBLE_DB_VERSION=!1,Pn);function Rn(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?Mn[a]:c;d=d===void 0?On[a]:d;e=e===void 0?Qn[a]:e;V.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Rn.prototype)}
y(Rn,V);function Sn(a,b){Rn.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Mn.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Sn.prototype)}
y(Sn,Rn);function Tn(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Tn.prototype)}
y(Tn,Error);var Un=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Vn(a,b,c,d){b=In(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Rn)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Rn("QUOTA_EXCEEDED",a);if(He&&e.name==="UnknownError")return new Rn("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Tn)return new Rn("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Un.some(function(f){return e.message.includes(f)}))return new Rn("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Rn("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",kd:e.name})];e.level="WARNING";return e}
function Wn(a,b,c){var d=xn();return new Rn("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Xn(a){if(!a)throw Error();throw a;}
function Yn(a){return a}
function Zn(a){this.h=a}
function $n(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=x(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=x(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
$n.all=function(a){return new $n(new Zn(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={rb:0};f.rb<a.length;f={rb:f.rb},++f.rb)$n.resolve(a[f.rb]).then(function(g){return function(h){d[g.rb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
$n.resolve=function(a){return new $n(new Zn(function(b,c){a instanceof $n?a.then(b,c):b(a)}))};
$n.reject=function(a){return new $n(new Zn(function(b,c){c(a)}))};
$n.prototype.then=function(a,b){var c=this,d=a!=null?a:Yn,e=b!=null?b:Xn;return new $n(new Zn(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){ao(c,c,d,f,g)}),c.i.push(function(){bo(c,c,e,f,g)})):c.state.status==="FULFILLED"?ao(c,c,d,f,g):c.state.status==="REJECTED"&&bo(c,c,e,f,g)}))};
$n.prototype.catch=function(a){return this.then(void 0,a)};
function ao(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof $n?co(a,b,f,d,e):d(f)}catch(g){e(g)}}
function bo(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof $n?co(a,b,f,d,e):d(f)}catch(g){e(g)}}
function co(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof $n?co(a,b,f,d,e):d(f)},function(f){e(f)})}
;function eo(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function fo(a){return new Promise(function(b,c){eo(a,b,c)})}
function go(a){return new $n(new Zn(function(b,c){eo(a,b,c)}))}
;function ho(a,b){return new $n(new Zn(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var io=window,W=io.ytcsi&&io.ytcsi.now?io.ytcsi.now:io.performance&&io.performance.timing&&io.performance.now&&io.performance.timing.navigationStart?function(){return io.performance.timing.navigationStart+io.performance.now()}:function(){return(new Date).getTime()};function jo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(W());this.i=!1}
p=jo.prototype;p.add=function(a,b,c){return ko(this,[a],{mode:"readwrite",la:!0},function(d){return d.objectStore(a).add(b,c)})};
p.clear=function(a){return ko(this,[a],{mode:"readwrite",la:!0},function(b){return b.objectStore(a).clear()})};
p.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
p.count=function(a,b){return ko(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).count(b)})};
function lo(a,b,c){a=a.h.createObjectStore(b,c);return new mo(a)}
p.delete=function(a,b){return ko(this,[a],{mode:"readwrite",la:!0},function(c){return c.objectStore(a).delete(b)})};
p.get=function(a,b){return ko(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).get(b)})};
function no(a,b,c){return ko(a,[b],{mode:"readwrite",la:!0},function(d){d=d.objectStore(b);return go(d.h.put(c,void 0))})}
p.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function ko(a,b,c,d){var e,f,g,h,k,l,n,m,r,t,v,u;return A(function(z){switch(z.h){case 1:var F={mode:"readonly",la:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?F.mode=c:Object.assign(F,c);e=F;a.transactionCount++;f=e.la?3:1;g=0;case 2:if(h){z.B(4);break}g++;k=Math.round(W());Aa(z,5);l=a.h.transaction(b,e.mode);F=z.yield;var I=new oo(l);I=po(I,d);return F.call(z,I,7);case 7:return n=z.i,m=Math.round(W()),qo(a,k,m,g,void 0,b.join(),e),z.return(n);case 5:r=Ba(z);t=Math.round(W());v=Vn(r,
a.h.name,b.join(),a.h.version);if((u=v instanceof Rn&&!v.h)||g>=f)qo(a,k,t,g,v,b.join(),e),h=v;z.B(2);break;case 4:return z.return(Promise.reject(h))}})}
function qo(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Rn&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&Gn("QUOTA_EXCEEDED",{dbName:In(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Rn&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=Math.pow(2,31)&&(c=0),Gn("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),ro(a,!1,d,f,b,g.tag),Fn(e)):ro(a,!0,d,f,b,g.tag)}
function ro(a,b,c,d,e,f){Gn("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
p.getName=function(){return this.h.name};
function mo(a){this.h=a}
p=mo.prototype;p.add=function(a,b){return go(this.h.add(a,b))};
p.autoIncrement=function(){return this.h.autoIncrement};
p.clear=function(){return go(this.h.clear()).then(function(){})};
function so(a,b,c){a.h.createIndex(b,c,{unique:!1})}
p.count=function(a){return go(this.h.count(a))};
function to(a,b){return uo(a,{query:b},function(c){return c.delete().then(function(){return vo(c)})}).then(function(){})}
p.delete=function(a){return a instanceof IDBKeyRange?to(this,a):go(this.h.delete(a))};
p.get=function(a){return go(this.h.get(a))};
p.index=function(a){try{return new wo(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Tn(a,this.h.name);throw b;}};
p.getName=function(){return this.h.name};
p.keyPath=function(){return this.h.keyPath};
function uo(a,b,c){a=a.h.openCursor(b.query,b.direction);return xo(a).then(function(d){return ho(d,c)})}
function oo(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Rn;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function po(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return x(d).next().value})}
oo.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Rn("EXPLICIT_ABORT");};
oo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new mo(a),this.i.set(a,b));return b};
function wo(a){this.h=a}
p=wo.prototype;p.count=function(a){return go(this.h.count(a))};
p.delete=function(a){return yo(this,{query:a},function(b){return b.delete().then(function(){return vo(b)})})};
p.get=function(a){return go(this.h.get(a))};
p.keyPath=function(){return this.h.keyPath};
p.unique=function(){return this.h.unique};
function yo(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return xo(a).then(function(d){return ho(d,c)})}
function zo(a,b){this.request=a;this.cursor=b}
function xo(a){return go(a).then(function(b){return b?new zo(a,b):null})}
function vo(a){a.cursor.continue(void 0);return xo(a.request)}
zo.prototype.delete=function(){return go(this.cursor.delete()).then(function(){})};
zo.prototype.getValue=function(){return this.cursor.value};
zo.prototype.update=function(a){return go(this.cursor.update(a))};function Ao(a,b,c){return new Promise(function(d,e){function f(){r||(r=new jo(g.result,{closed:m}));return r}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Kd,k=c.blocking,l=c.Ye,n=c.upgrade,m=c.closed,r;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&Gn("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:In(a)});var v=f(),u=new oo(g.transaction);
n&&n(v,function(z){return t.oldVersion<z&&t.newVersion>=z},u);
u.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){Gn("IDB_UNEXPECTEDLY_CLOSED",{dbName:In(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Bo(a,b,c){c=c===void 0?{}:c;return Ao(a,b,c)}
function Co(a,b){b=b===void 0?{}:b;var c,d,e,f;return A(function(g){if(g.h==1)return Aa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Kd)&&c.addEventListener("blocked",function(){e()}),g.yield(fo(c),4);
if(g.h!=2)g.h=0,g.l=0;else throw f=Ba(g),Vn(f,a,"",-1);})}
;function Do(a,b){this.name=a;this.options=b;this.j=!0;this.v=this.l=0}
Do.prototype.i=function(a,b,c){c=c===void 0?{}:c;return Bo(a,b,c)};
Do.prototype.delete=function(a){a=a===void 0?{}:a;return Co(this.name,a)};
function Eo(a,b){return new Rn("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Fo(a,b){if(!b)throw Wn("openWithToken",In(a.name));return a.open()}
Do.prototype.open=function(){function a(){var f,g,h,k,l,n,m,r,t,v;return A(function(u){switch(u.h){case 1:return g=(f=Error().stack)!=null?f:"",Aa(u,2),u.yield(c.i(c.name,c.options.version,e),4);case 4:for(var z=h=u.i,F=c.options,I=[],O=x(Object.keys(F.yb)),S=O.next();!S.done;S=O.next()){S=S.value;var da=F.yb[S],ta=da.Be===void 0?Number.MAX_VALUE:da.Be;!(z.h.version>=da.Gb)||z.h.version>=ta||z.h.objectStoreNames.contains(S)||I.push(S)}k=I;if(k.length===0){u.B(5);break}l=Object.keys(c.options.yb);
n=h.objectStoreNames();if(c.v<Ll("ytidb_reopen_db_retries",0))return c.v++,h.close(),Fn(new Rn("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),u.return(a());if(!(c.l<Ll("ytidb_remake_db_retries",1))){u.B(6);break}c.l++;return u.yield(c.delete(),7);case 7:return Fn(new Rn("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),u.return(a());case 6:throw new Sn(n,l);case 5:return u.return(h);case 2:m=Ba(u);
if(m instanceof DOMException?m.name!=="VersionError":"DOMError"in self&&m instanceof DOMError?m.name!=="VersionError":!(m instanceof Object&&"message"in m)||m.message!=="An attempt was made to open a database using a lower version than the existing version."){u.B(8);break}return u.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:r=u.i;t=r.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw r.close(),c.j=!1,Eo(c,t);return u.return(r);case 8:throw b(),m instanceof
Error&&!U("ytidb_async_stack_killswitch")&&(m.stack=m.stack+"\n"+g.substring(g.indexOf("\n")+1)),Vn(m,c.name,"",(v=c.options.version)!=null?v:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw Eo(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Ye:b,upgrade:this.options.upgrade};return this.h=d=a()};var Go=new Do("YtIdbMeta",{yb:{databases:{Gb:1}},upgrade:function(a,b){b(1)&&lo(a,"databases",{keyPath:"actualName"})}});
function Ho(a,b){var c;return A(function(d){if(d.h==1)return d.yield(Fo(Go,b),2);c=d.i;return d.return(ko(c,["databases"],{la:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return go(f.h.put(a,void 0)).then(function(){})})}))})}
function Io(a,b){var c;return A(function(d){if(d.h==1)return a?d.yield(Fo(Go,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Jo(a,b){var c,d;return A(function(e){return e.h==1?(c=[],e.yield(Fo(Go,b),2)):e.h!=3?(d=e.i,e.yield(ko(d,["databases"],{la:!0,mode:"readonly"},function(f){c.length=0;return uo(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return vo(g)})}),3)):e.return(c)})}
function Ko(a){return Jo(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function Lo(a,b,c){return Jo(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function Mo(a){var b,c;return A(function(d){if(d.h==1)return b=Nm("YtIdbMeta hasAnyMeta other"),d.yield(Jo(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var No,Oo=new function(){}(new function(){});
function Po(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=xn();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Jn)f=/WebKit\/([0-9]+)/.exec(Lc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Lc()),f=!(f&&parseInt(f[1],10)>=602));if(f||Yc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
Aa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(Ho(d,Oo),4);case 4:return e.yield(Io("yt-idb-test-do-not-use",Oo),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function Qo(){if(No!==void 0)return No;An=!0;return No=Po().then(function(a){An=!1;var b;if((b=wn())!=null&&b.h){var c;b={hasSucceededOnce:((c=xn())==null?void 0:c.hasSucceededOnce)||a};var d;(d=wn())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Ro(){return E("ytglobal.idbToken_")||void 0}
function So(){var a=Ro();return a?Promise.resolve(a):Qo().then(function(b){(b=b?Oo:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var To=0;function Uo(a,b){To||(To=Xi.pa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(So(),2);case 2:c=h.i;if(!c)return h.return();d=!0;Aa(h,3);return h.yield(Lo(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.B(6);break}f=e[0];return h.yield(Co(f.actualName),7);case 7:return h.yield(Io(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=Ba(h),Fn(g),d=!1;case 4:Xi.qa(To),To=0,d&&Uo(a,b),h.h=0}})}))}
function Vo(){var a;return A(function(b){return b.h==1?b.yield(So(),2):(a=b.i)?b.return(Mo(a)):b.return(!1)})}
new Gi;function Wo(a){if(!Mm())throw a=new Rn("AUTH_INVALID",{dbName:a}),Fn(a),a;var b=Nm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Xo(a,b,c,d){var e,f,g,h,k,l;return A(function(n){switch(n.h){case 1:return f=(e=Error().stack)!=null?e:"",n.yield(So(),2);case 2:g=n.i;if(!g)throw h=Wn("openDbImpl",a,b),U("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),Fn(h),h;Hn(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Wo(a);Aa(n,3);return n.yield(Ho(k,g),5);case 5:return n.yield(Bo(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=Ba(n),Aa(n,7),n.yield(Io(k.actualName,
g),9);case 9:n.h=8;n.l=0;break;case 7:Ba(n);case 8:throw l;}})}
function Yo(a,b,c){c=c===void 0?{}:c;return Xo(a,b,!1,c)}
function Zo(a,b,c){c=c===void 0?{}:c;return Xo(a,b,!0,c)}
function $o(a,b){b=b===void 0?{}:b;var c,d;return A(function(e){if(e.h==1)return e.yield(So(),2);if(e.h!=3){c=e.i;if(!c)return e.return();Hn(a);d=Wo(a);return e.yield(Co(d.actualName,b),3)}return e.yield(Io(d.actualName,c),0)})}
function ap(a,b,c){a=a.map(function(d){return A(function(e){return e.h==1?e.yield(Co(d.actualName,b),2):e.yield(Io(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function bp(){var a=a===void 0?{}:a;var b,c;return A(function(d){if(d.h==1)return d.yield(So(),2);if(d.h!=3){b=d.i;if(!b)return d.return();Hn("LogsDatabaseV2");return d.yield(Ko(b),3)}c=d.i;return d.yield(ap(c,a,b),0)})}
function cp(a,b){b=b===void 0?{}:b;var c;return A(function(d){if(d.h==1)return d.yield(So(),2);if(d.h!=3){c=d.i;if(!c)return d.return();Hn(a);return d.yield(Co(a,b),3)}return d.yield(Io(a,c),0)})}
;function dp(a,b){Do.call(this,a,b);this.options=b;Hn(a)}
y(dp,Do);function ep(a,b){var c;return function(){c||(c=new dp(a,b));return c}}
dp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Zo:Yo)(a,b,Object.assign({},c))};
dp.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?cp:$o)(this.name,a)};
function fp(a,b){return ep(a,b)}
;var gp={},hp=fp("ytGcfConfig",{yb:(gp.coldConfigStore={Gb:1},gp.hotConfigStore={Gb:1},gp),shared:!1,upgrade:function(a,b){b(1)&&(so(lo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),so(lo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function ip(a){return Fo(hp(),a)}
function jp(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:W()},g.yield(ip(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(no(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function kp(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:W()},h.yield(ip(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(no(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function lp(a){var b,c;return A(function(d){return d.h==1?d.yield(ip(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(ko(b,["coldConfigStore"],{mode:"readwrite",la:!0},function(e){return yo(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function mp(a){var b,c;return A(function(d){return d.h==1?d.yield(ip(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(ko(b,["hotConfigStore"],{mode:"readwrite",la:!0},function(e){return yo(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function np(){G.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(la(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
y(np,G);np.prototype.U=function(){for(var a=x(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;G.prototype.U.call(this)};function op(){this.h=0;this.i=new np}
function pp(){var a;return(a=E("yt.gcf.config.hotConfigGroup"))!=null?a:T("RAW_HOT_CONFIG_GROUP")}
function qp(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!U("start_client_gcf")){g.B(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.l(b);d=Ro();if(!d){g.B(3);break}if(c){g.B(4);break}return g.yield(mp(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(jp(c,b,d),3);case 3:if(c)for(var h=c,k=x(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function rp(a,b,c){var d,e,f,g;return A(function(h){if(h.h==1){if(!U("start_client_gcf"))return h.B(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Ro())?c?h.B(4):h.yield(lp(d),5):h.B(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.B(0);g=c.configData;return h.yield(kp(c,b,g,d),0)})}
function sp(){if(!op.h){var a=new op;op.h=a}a=op.h;var b=W()-a.h;if(!(a.h!==0&&b<Ll("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=W());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
op.prototype.l=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function tp(){return"INNERTUBE_API_KEY"in ll&&"INNERTUBE_API_VERSION"in ll}
function up(){return{innertubeApiKey:T("INNERTUBE_API_KEY"),innertubeApiVersion:T("INNERTUBE_API_VERSION"),de:T("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),cd:T("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Eg:T("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:T("INNERTUBE_CONTEXT_CLIENT_VERSION"),ge:T("INNERTUBE_CONTEXT_HL"),ee:T("INNERTUBE_CONTEXT_GL"),he:T("INNERTUBE_HOST_OVERRIDE")||"",ke:!!T("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),je:!!T("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:T("SERIALIZED_CLIENT_CONFIG_DATA")}}
function vp(a){var b={client:{hl:a.ge,gl:a.ee,clientName:a.cd,clientVersion:a.innertubeContextClientVersion,configInfo:a.de}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=T("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=Ml();c.length>0&&(b.request={internalExperimentFlags:c});c=a.cd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=pm()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(U("web_log_memory_total_kbytes")&&((e=C.navigator)==null?0:e.deviceMemory)){var f;e=(f=C.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=Km())&&b&&(b.client.connectionType=a);U("web_log_effective_connection_type")&&
(a=Lm())&&b&&(b.client.effectiveConnectionType=a);U("start_client_gcf")&&(e=sp())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));T("DELEGATED_SESSION_ID")&&!U("pageid_as_header_web")&&(b.user={onBehalfOfUser:T("DELEGATED_SESSION_ID")});!U("fill_delegate_context_in_gel_killswitch")&&(a=T("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=x(Object.entries(zl(T("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=x(g.value);g=h.next().value;h=h.next().value;g==="cbrand"?d.deviceMake=h:g==="cmodel"?d.deviceModel=h:g==="cbr"?d.browserName=h:g==="cbrver"?d.browserVersion=h:g==="cos"?d.osName=h:g==="cosver"?d.osVersion=h:g==="cplatform"&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function wp(a,b,c){c=c===void 0?{}:c;var d={};T("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":T("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||T("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||T("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().xg:(a=sm(rm()),U("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var xp=typeof TextEncoder!=="undefined"?new TextEncoder:null,yp=xp?function(a){return xp.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function zp(a,b){this.version=a;this.args=b}
zp.prototype.serialize=function(){return{version:this.version,args:this.args}};function Ap(a,b){this.topic=a;this.h=b}
Ap.prototype.toString=function(){return this.topic};var Bp=E("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Cb;M.prototype.publish=M.prototype.Ya;M.prototype.clear=M.prototype.clear;D("ytPubsub2Pubsub2Instance",Bp);var Cp=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",Cp);var Dp=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",Dp);var Ep=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",Ep);
D("ytPubsub2Pubsub2SkipSubKey",null);function Fp(a,b){var c=Gp();c&&c.publish.call(c,a.toString(),a,b)}
function Hp(a){var b=Ip,c=Gp();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Cp[d])try{if(f&&b instanceof Ap&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Ad){var l=new h;h.Ad=l.version}var n=h.Ad}catch(z){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var m=n.construct;
var r=k.args,t=r.length;if(t>0){var v=Array(t);for(k=0;k<t;k++)v[k]=r[k];var u=v}else u=[];f=m.call(n,h,u)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){rl(z)}},Ep[b.toString()]?E("yt.scheduler.instance")?Xi.pa(g):Il(g,0):g())});
Cp[d]=!0;Dp[b.toString()]||(Dp[b.toString()]=[]);Dp[b.toString()].push(d);return d}
function Jp(){var a=Kp,b=Hp(function(c){a.apply(void 0,arguments);Lp(b)});
return b}
function Lp(a){var b=Gp();b&&(typeof a==="number"&&(a=[a]),Db(a,function(c){b.unsubscribeByKey(c);delete Cp[c]}))}
function Gp(){return E("ytPubsub2Pubsub2Instance")}
;function Mp(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&Fp("meta_logging_csi_event",{timerName:a,Ug:b})}
;var Np=void 0,Op=void 0;function Pp(){Op||(Op=Lk(T("WORKER_SERIALIZATION_URL")));return Op||void 0}
function Qp(){var a=Pp();Np||a===void 0||(Np=new Worker(kb(a),void 0));return Np}
;var Rp=Ll("max_body_size_to_compress",5E5),Sp=Ll("min_body_size_to_compress",500),Tp=!0,Up=0,Vp=0,Wp=Ll("compression_performance_threshold_lr",250),Xp=Ll("slow_compressions_before_abandon_count",4),Yp=!1,Zp=new Map,$p=1,aq=!0;function bq(){if(typeof Worker==="function"&&Pp()&&!Yp){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Zp.get(c.key);d&&(cq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Zp.delete(c.key))}},b=Qp();
b&&(b.addEventListener("message",a),b.onerror=function(){Zp.clear()},Yp=!0)}}
function dq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:W(),ticks:{},infos:{}};if(Tp)try{var g=eq(b);if(g!=null&&(g>Rp||g<Sp))d(a,c);else{if(U("gzip_gel_with_worker")&&(U("initial_gzip_use_main_thread")&&!aq||!U("initial_gzip_use_main_thread"))){Yp||bq();var h=Qp();if(h&&!e){Zp.set($p,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:$p});$p++;return}}var k=Kk(yp(b));cq(k,f,a,c,d)}}catch(l){sl(l),d(a,c)}else d(a,c)}
function cq(a,b,c,d,e){aq=!1;var f=W();b.ticks.gelc=f;Vp++;U("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Wp&&(Up++,U("abandon_compression_after_N_slow_zips")?Vp===Ll("compression_disable_point")&&Up>Xp&&(Tp=!1):Tp=!1);fq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function gq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=W(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(Tp&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=eq(g);if(h!=null&&(h>Rp||h<Sp))return a;c=b?{level:1}:void 0;f=Kk(yp(g),c);var k=W();e.ticks.gelc=k;if(b){Vp++;if((U("disable_compression_due_to_performance_degredation")||U("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Wp)if(Up++,U("abandon_compression_after_N_slow_zips")||U("abandon_compression_after_N_slow_zips_lr")){b=Up/Vp;var l=Xp/Ll("compression_disable_point");Vp>0&&Vp%Ll("compression_disable_point")===0&&b>=l&&(Tp=!1)}else Tp=!1;fq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(n){return sl(n),a}}else return a}
function eq(a){try{return(new Blob(a.split(""))).size}catch(b){return sl(b),null}}
function fq(a){U("gel_compression_csi_killswitch")||!U("log_gel_compression_latency")&&!U("log_gel_compression_latency_lr")||Mp("gel_compression",a,{sampleRate:.1})}
;function hq(a){a=Object.assign({},a);delete a.Authorization;var b=wh();if(b){var c=new aj;c.update(T("INNERTUBE_API_KEY"));c.update(b);a.hash=Ke(c.digest(),3)}return a}
;var iq;function jq(){iq||(iq=new vn("yt.innertube"));return iq}
function kq(a,b,c,d){if(d)return null;d=jq().get("nextId",!0)||1;var e=jq().get("requests",!0)||{};e[d]={method:a,request:b,authState:hq(c),requestTime:Math.round(W())};jq().set("nextId",d+1,86400,!0);jq().set("requests",e,86400,!0);return d}
function lq(a){var b=jq().get("requests",!0)||{};delete b[a];jq().set("requests",b,86400,!0)}
function mq(a){var b=jq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(W())-d.requestTime<6E4)){var e=d.authState,f=hq(wp(!1));Qb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(W())),nq(a,d.method,e,{}));delete b[c]}}jq().set("requests",b,86400,!0)}}
;function oq(a){this.Wb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.pb=function(){};
this.now=Date.now;this.Jb=!1;var b;this.xd=(b=a.xd)!=null?b:100;var c;this.rd=(c=a.rd)!=null?c:1;var d;this.od=(d=a.od)!=null?d:2592E6;var e;this.md=(e=a.md)!=null?e:12E4;var f;this.qd=(f=a.qd)!=null?f:5E3;var g;this.X=(g=a.X)!=null?g:void 0;this.cc=!!a.cc;var h;this.Zb=(h=a.Zb)!=null?h:.1;var k;this.kc=(k=a.kc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.pb&&(this.pb=a.pb);a.Jb&&(this.Jb=a.Jb);a.Wb&&(this.Wb=a.Wb);this.Y=a.Y;this.Da=a.Da;this.ha=a.ha;this.fa=a.fa;this.sendFn=a.sendFn;
this.Hc=a.Hc;this.Ec=a.Ec;pq(this)&&(!this.Y||this.Y("networkless_logging"))&&qq(this)}
function qq(a){pq(a)&&!a.Jb&&(a.h=!0,a.cc&&Math.random()<=a.Zb&&a.ha.Ld(a.X),rq(a),a.fa.va()&&a.Sb(),a.fa.listen(a.Hc,a.Sb.bind(a)),a.fa.listen(a.Ec,a.Rc.bind(a)))}
p=oq.prototype;p.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(pq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ha.set(d,this.X).then(function(e){d.id=e;c.fa.va()&&sq(c,d)}).catch(function(e){sq(c,d);
tq(c,e)})}else this.sendFn(a,b)};
p.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(pq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y&&this.Y("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.va()||this.Y&&this.Y("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(k.h==1)return k.yield(d.ha.set(e,d.X).catch(function(l){tq(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ha.set(e,this.X).catch(function(g){d.sendFn(a,b,e.skipRetry);
tq(d,g)})}else this.sendFn(a,b,this.Y&&this.Y("nwl_skip_retry")&&c)};
p.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(pq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ha.ob(d.id,c.X):e=!0;c.fa.gb&&c.Y&&c.Y("vss_network_hint")&&c.fa.gb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ha.set(d,this.X).then(function(g){d.id=g;e&&c.ha.ob(d.id,c.X)}).catch(function(g){tq(c,g)})}else this.sendFn(a,b,void 0,!0)};
p.Sb=function(){var a=this;if(!pq(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Da.pa(function(){var b;return A(function(c){if(c.h==1)return c.yield(a.ha.Yc("NEW",a.X),2);if(c.h!=3)return b=c.i,b?c.yield(sq(a,b),3):(a.Rc(),c.return());a.i&&(a.i=0,a.Sb());c.h=0})},this.xd))};
p.Rc=function(){this.Da.qa(this.i);this.i=0};
function sq(a,b){var c;return A(function(d){switch(d.h){case 1:if(!pq(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.B(2);break}return d.yield(a.ha.ne(b.id,a.X),3);case 3:(c=d.i)||a.pb(Error("The request cannot be found in the database."));case 2:if(uq(a,b,a.od)){d.B(4);break}a.pb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.B(5);break}return d.yield(a.ha.ob(b.id,a.X),5);case 5:return d.return();case 4:b.skipRetry||(b=vq(a,
b));if(!b){d.B(0);break}if(!b.skipRetry||b.id===void 0){d.B(8);break}return d.yield(a.ha.ob(b.id,a.X),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function vq(a,b){if(!pq(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(n){switch(n.h){case 1:g=wq(f);(h=xq(f))&&a.Y&&a.Y("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.Y&&a.Y("nwl_consider_error_code")&&g||a.Y&&!a.Y("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.kc)){n.B(2);break}if(!a.fa.nc){n.B(3);break}return n.yield(a.fa.nc(),3);case 3:if(a.fa.va()){n.B(2);break}c(e,f);if(!a.Y||!a.Y("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){n.B(6);
break}return n.yield(a.ha.Ic(b.id,a.X,!1),6);case 6:return n.return();case 2:if(a.Y&&a.Y("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.kc)return n.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){n.B(8);break}return b.sendCount<a.rd?n.yield(a.ha.Ic(b.id,a.X,!0,h?!1:void 0),12):n.yield(a.ha.ob(b.id,a.X),8);case 12:a.Da.pa(function(){a.fa.va()&&a.Sb()},a.qd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.B(2):h.yield(a.ha.ob(b.id,a.X),2);a.fa.gb&&a.Y&&a.Y("vss_network_hint")&&a.fa.gb(!0);d(e,f);h.h=0})};
return b}
function uq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function rq(a){if(!pq(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ha.Yc("QUEUED",a.X).then(function(b){b&&!uq(a,b,a.md)?a.Da.pa(function(){return A(function(c){if(c.h==1)return b.id===void 0?c.B(2):c.yield(a.ha.Ic(b.id,a.X),2);rq(a);c.h=0})}):a.fa.va()&&a.Sb()})}
function tq(a,b){a.Dd&&!a.fa.va()?a.Dd(b):a.handleError(b)}
function pq(a){return!!a.X||a.Wb}
function wq(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function xq(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var yq;
function zq(){if(yq)return yq();var a={};yq=fp("LogsDatabaseV2",{yb:(a.LogsRequestsStore={Gb:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&lo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),so(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return yq()}
;function Aq(a){return Fo(zq(),a)}
function Bq(a,b){var c,d,e,f;return A(function(g){if(g.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(Aq(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:T("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(no(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=W();Cq(c);return g.return(f)})}
function Dq(a,b){var c,d,e,f,g,h,k,l;return A(function(n){if(n.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},n.yield(Aq(b),2);if(n.h!=3)return d=n.i,e=T("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,W()],h=IDBKeyRange.bound(f,g),k="prev",U("use_fifo_for_networkless")&&(k="next"),l=void 0,n.yield(ko(d,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(m){return yo(m.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(r){r.getValue()&&(l=r.getValue(),a==="NEW"&&(l.status="QUEUED",r.update(l)))})}),3);
c.ticks.tc=W();Cq(c);return n.return(l)})}
function Eq(a,b){var c;return A(function(d){if(d.h==1)return d.yield(Aq(b),2);c=d.i;return d.return(ko(c,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",go(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Fq(a,b,c,d){c=c===void 0?!0:c;var e;return A(function(f){if(f.h==1)return f.yield(Aq(b),2);e=f.i;return f.return(ko(e,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),go(h.h.put(k,void 0)).then(function(){return k})):$n.resolve(void 0)})}))})}
function Gq(a,b){var c;return A(function(d){if(d.h==1)return d.yield(Aq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Hq(a){var b,c;return A(function(d){if(d.h==1)return d.yield(Aq(a),2);b=d.i;c=W()-2592E6;return d.yield(ko(b,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){return uo(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return vo(f)})})}),0)})}
function Iq(){A(function(a){return a.yield(bp(),0)})}
function Cq(a){U("nwl_csi_killswitch")||Mp("networkless_performance",a,{sampleRate:1})}
;var Jq={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,
mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,
kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
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
miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500};var Kq={},Lq=fp("ServiceWorkerLogsDatabase",{yb:(Kq.SWHealthLog={Gb:1},Kq),shared:!0,upgrade:function(a,b){b(1)&&so(lo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Mq(a){return Fo(Lq(),a)}
function Nq(a){var b,c;A(function(d){if(d.h==1)return d.yield(Mq(a),2);b=d.i;c=W()-2592E6;return d.yield(ko(b,["SWHealthLog"],{mode:"readwrite",la:!0},function(e){return uo(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return vo(f)})})}),0)})}
function Oq(a){var b;return A(function(c){if(c.h==1)return c.yield(Mq(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Pq={},Qq=0;function Rq(a){var b=new Image,c=""+Qq++;Pq[c]=b;b.onload=b.onerror=function(){delete Pq[c]};
b.src=a}
;var Sq;function Tq(){Sq||(Sq=new vn("yt.offline"));return Sq}
function Uq(a){if(U("offline_error_handling")){var b=Tq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Tq().set("errors",b,2592E3,!0)}}
;function Vq(){this.h=new Map;this.i=!1}
function Wq(){if(!Vq.h){var a=E("yt.networkRequestMonitor.instance")||new Vq;D("yt.networkRequestMonitor.instance",a);Vq.h=a}return Vq.h}
Vq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Vq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Vq.prototype.removeParams=function(a){return a.split("?")[0]};
Vq.prototype.removeParams=Vq.prototype.removeParams;Vq.prototype.isEndpointCFR=Vq.prototype.isEndpointCFR;Vq.prototype.requestComplete=Vq.prototype.requestComplete;Vq.getInstance=Wq;function Xq(){yd.call(this);var a=this;this.j=!1;this.i=Wi();this.i.listen("networkstatus-online",function(){if(a.j&&U("offline_error_handling")){var b=Tq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new V(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;rl(d)}Tq().set("errors",{},2592E3,!0)}}})}
y(Xq,yd);function Yq(){if(!Xq.h){var a=E("yt.networkStatusManager.instance")||new Xq;D("yt.networkStatusManager.instance",a);Xq.h=a}return Xq.h}
p=Xq.prototype;p.va=function(){return this.i.va()};
p.gb=function(a){this.i.i=a};
p.Zd=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
p.Qd=function(){this.j=!0};
p.listen=function(a,b){return this.i.listen(a,b)};
p.nc=function(a){a=Ui(this.i,a);a.then(function(b){U("use_cfr_monitor")&&Wq().requestComplete("generate_204",b)});
return a};
Xq.prototype.sendNetworkCheckRequest=Xq.prototype.nc;Xq.prototype.listen=Xq.prototype.listen;Xq.prototype.enableErrorFlushing=Xq.prototype.Qd;Xq.prototype.getWindowStatus=Xq.prototype.Zd;Xq.prototype.networkStatusHint=Xq.prototype.gb;Xq.prototype.isNetworkAvailable=Xq.prototype.va;Xq.getInstance=Yq;function Zq(a){a=a===void 0?{}:a;yd.call(this);var b=this;this.i=this.m=0;this.j=Yq();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){$q(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){$q(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){zd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){zd(b,"publicytnetworkstatus-offline")})))}
y(Zq,yd);Zq.prototype.va=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Zq.prototype.gb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Zq.prototype.nc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return U("skip_network_check_if_cfr")&&Wq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.gb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.va())})):c?d.return(c(a)):d.return(!0)})};
function $q(a,b){a.rateLimit?a.i?(Xi.qa(a.m),a.m=Xi.pa(function(){a.l!==b&&(zd(a,b),a.l=b,a.i=W())},a.rateLimit-(W()-a.i))):(zd(a,b),a.l=b,a.i=W()):zd(a,b)}
;var ar;function br(){var a=oq.call;ar||(ar=new Zq({Jg:!0,Cg:!0}));a.call(oq,this,{ha:{Ld:Hq,ob:Gq,Yc:Dq,ne:Eq,Ic:Fq,set:Bq},fa:ar,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;sl(new V(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else rl(b)},
pb:sl,sendFn:cr,now:W,Dd:Uq,Da:un(),Hc:"publicytnetworkstatus-online",Ec:"publicytnetworkstatus-offline",cc:!0,Zb:.1,kc:Ll("potential_esf_error_limit",10),Y:U,Jb:!(Mm()&&dr())});this.j=new Gi;U("networkless_immediately_drop_all_requests")&&Iq();cp("LogsDatabaseV2")}
y(br,oq);function er(){var a=E("yt.networklessRequestController.instance");a||(a=new br,D("yt.networklessRequestController.instance",a),U("networkless_logging")&&So().then(function(b){a.X=b;qq(a);a.j.resolve();a.cc&&Math.random()<=a.Zb&&a.X&&Nq(a.X);U("networkless_immediately_drop_sw_health_store")&&fr(a)}));
return a}
br.prototype.writeThenSend=function(a,b){b||(b={});b=gr(a,b);Mm()||(this.h=!1);oq.prototype.writeThenSend.call(this,a,b)};
br.prototype.sendThenWrite=function(a,b,c){b||(b={});b=gr(a,b);Mm()||(this.h=!1);oq.prototype.sendThenWrite.call(this,a,b,c)};
br.prototype.sendAndWrite=function(a,b){b||(b={});b=gr(a,b);Mm()||(this.h=!1);oq.prototype.sendAndWrite.call(this,a,b)};
br.prototype.awaitInitialization=function(){return this.j.promise};
function fr(a){var b;A(function(c){if(!a.X)throw b=Wn("clearSWHealthLogsDb"),b;return c.return(Oq(a.X).catch(function(d){a.handleError(d)}))})}
function cr(a,b,c,d){d=d===void 0?!1:d;b=U("web_fp_via_jspb")?Object.assign({},b):b;U("use_cfr_monitor")&&hr(a,b);if(U("use_request_time_ms_header"))b.headers&&Cl(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(W())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Ql(a,void 0,"POST",f,void 0);else if(T("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Ql(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new cb({url:a});if(k.j&&k.i||k.l){var l=mc(nc(5,a)),n;if(!(n=!l||!l.endsWith("/aclk"))){var m=a.search(vc),r=uc(a,0,"ri",m);if(r<0)var t=null;else{var v=a.indexOf("&",r);if(v<0||v>m)v=m;t=decodeURIComponent(a.slice(r+3,v!==-1?v:0).replace(/\+/g," "))}n=t!=="1"}var u=!n;break b}}catch(F){}u=!1}if(u){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(F){}z=!1}c=z?!0:!1}else c=
!1;c||Rq(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),dq(a,b.postBody,b,Ul,d)):dq(a,JSON.stringify(b.postParams),b,Tl,d):Ul(a,b)}
function gr(a,b){U("use_event_time_ms_header")&&Cl(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(W())));return b}
function hr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Wq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Wq().requestComplete(a,!0);d(e,f)}}
function dr(){return oc(document.location.toString())!=="www.youtube-nocookie.com"}
;var ir=!1,jr=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:ir};D("ytNetworklessLoggingInitializationOptions",jr);function kr(){var a;A(function(b){if(b.h==1)return b.yield(So(),2);a=b.i;if(!a||!Mm()&&!U("nwl_init_require_datasync_id_killswitch")||!dr())return b.B(0);ir=!0;jr.isNwlInitialized=ir;return b.yield(er().awaitInitialization(),0)})}
;function lr(a){var b=this;this.config_=null;a?this.config_=a:tp()&&(this.config_=up());Pm(function(){mq(b)},5E3)}
lr.prototype.isReady=function(){!this.config_&&tp()&&(this.config_=up());return!!this.config_};
function nq(a,b,c,d){function e(v){v=v===void 0?!1:v;var u;if(d.retry&&h!="www.youtube-nocookie.com"&&(v||U("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(u=kq(b,c,l,k)),u)){var z=g.onSuccess,F=g.onFetchSuccess;g.onSuccess=function(S,da){lq(u);z(S,da)};
c.onFetchSuccess=function(S,da){lq(u);F(S,da)}}try{if(v&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?er().writeThenSend(t,g):er().sendAndWrite(t,g);
else if(d.compress){var I=!d.networklessOptions.writeThenSend;if(g.postBody){var O=g.postBody;typeof O!=="string"&&(O=JSON.stringify(g.postBody));dq(t,O,g,Ul,I)}else dq(t,JSON.stringify(g.postParams),g,Tl,I)}else U("web_all_payloads_via_jspb")?Ul(t,g):Tl(t,g)}catch(S){if(S.name==="InvalidAccessError")u&&(lq(u),u=0),sl(Error("An extension is blocking network request."));else throw S;}u&&Pm(function(){mq(a)},5E3)}
!T("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&sl(new V("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new V("innertube xhrclient not ready",b,c,d);rl(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(v,u){if(d.onSuccess)d.onSuccess(u)},
onFetchSuccess:function(v){if(d.onSuccess)d.onSuccess(v)},
onError:function(v,u){if(d.onError)d.onError(u)},
onFetchError:function(v){if(d.onError)d.onError(v)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.he)&&(h=f);var k=a.config_.ke||!1,l=wp(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,m={alt:"json"},r=a.config_.je&&f;r=r&&f.startsWith("Bearer");r||(m.key=a.config_.innertubeApiKey);var t=Bl(""+h+n,m||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
jr.isNwlInitialized:ir)?Qo().then(function(v){e(v)}):e(!1)}
;var mr=0,nr=$c?"webkit":Zc?"moz":Xc?"ms":Wc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++mr});var or={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function pr(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in or||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function qr(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
pr.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
pr.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
pr.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var Mb=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",Mb);var ur=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",ur);
function vr(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return Lb(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&Qb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function wr(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=vr(a,b,c,d);if(e)return e;e=++ur.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new pr(h);if(!Jd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new pr(h);
h.currentTarget=a;return c.call(a,h)};
g=ql(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),xr()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);Mb[e]=[a,b,c,g,d];return e}
function yr(a){a&&(typeof a=="string"&&(a=[a]),Db(a,function(b){if(b in Mb){var c=Mb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?xr()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete Mb[b]}}))}
var xr=Ed(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function zr(a){this.H=a;this.h=null;this.l=0;this.A=null;this.m=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.W=wr(window,"mousemove",Xa(this.ba,this));a=Xa(this.P,this);typeof a==="function"&&(a=ql(a));this.da=window.setInterval(a,25)}
$a(zr,G);zr.prototype.ba=function(a){a.h===void 0&&qr(a);var b=a.h;a.i===void 0&&qr(a);this.h=new Fd(b,a.i)};
zr.prototype.P=function(){if(this.h){var a=W();if(this.l!=0){var b=this.A,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.l);this.i[this.j]=Math.abs((d-this.m)/this.m)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.H();this.m=d}this.l=a;this.A=this.h;this.j=(this.j+1)%4}};
zr.prototype.U=function(){window.clearInterval(this.da);yr(this.W)};var Ar={};
function Br(a){var b=a===void 0?{}:a;a=b.xe===void 0?!1:b.xe;b=b.Rd===void 0?!0:b.Rd;if(E("_lact",window)==null){var c=parseInt(T("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);c==-1&&Cr();wr(document,"keydown",Cr);wr(document,"keyup",Cr);wr(document,"mousedown",Cr);wr(document,"mouseup",Cr);a?wr(window,"touchmove",function(){Dr("touchmove",200)},{passive:!0}):(wr(window,"resize",function(){Dr("resize",200)}),b&&wr(window,"scroll",function(){Dr("scroll",200)}));
new zr(function(){Dr("mouse",100)});
wr(document,"touchstart",Cr,{passive:!0});wr(document,"touchend",Cr,{passive:!0})}}
function Dr(a,b){Ar[a]||(Ar[a]=!0,Xi.pa(function(){Cr();Ar[a]=!1},b))}
function Cr(){E("_lact",window)==null&&Br();var a=Date.now();D("_lact",a,window);E("_fact",window)==-1&&D("_fact",a,window);(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function Er(){var a=E("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var Fr=C.ytPubsubPubsubInstance||new M,Gr=C.ytPubsubPubsubSubscribedKeys||{},Hr=C.ytPubsubPubsubTopicToKeys||{},Ir=C.ytPubsubPubsubIsSynchronous||{};function Jr(a,b){var c=Kr();if(c&&b){var d=c.subscribe(a,function(){function e(){Gr[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{Ir[a]?e():Il(e,0)}catch(g){rl(g)}},void 0);
Gr[d]=!0;Hr[a]||(Hr[a]=[]);Hr[a].push(d);return d}return 0}
function Lr(a){var b=Kr();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Db(a,function(c){b.unsubscribeByKey(c);delete Gr[c]}))}
function Mr(a,b){var c=Kr();c&&c.publish.apply(c,arguments)}
function Nr(a){var b=Kr();if(b)if(b.clear(a),a)Or(a);else for(var c in Hr)Or(c)}
function Kr(){return C.ytPubsubPubsubInstance}
function Or(a){Hr[a]&&(a=Hr[a],Db(a,function(b){Gr[b]&&delete Gr[b]}),a.length=0)}
M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Cb;M.prototype.publish=M.prototype.Ya;M.prototype.clear=M.prototype.clear;D("ytPubsubPubsubInstance",Fr);D("ytPubsubPubsubTopicToKeys",Hr);D("ytPubsubPubsubIsSynchronous",Ir);D("ytPubsubPubsubSubscribedKeys",Gr);var Pr=Symbol("injectionDeps");function Qr(a){this.name=a}
Qr.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Rr(a){this.key=a}
function Sr(){this.i=new Map;this.j=new Map;this.h=new Map}
function Tr(a,b){a.i.set(b.mc,b);var c=a.j.get(b.mc);if(c)try{c.Qg(a.resolve(b.mc))}catch(d){c.Og(d)}}
Sr.prototype.resolve=function(a){return a instanceof Rr?Ur(this,a.key,[],!0):Ur(this,a,[])};
function Ur(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.zd!==void 0)var e=d.zd;else if(d.ff)e=d[Pr]?Vr(a,d[Pr],c):[],e=d.ff.apply(d,la(e));else if(d.yd){e=d.yd;var f=e[Pr]?Vr(a,e[Pr],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(la(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Tg||a.h.set(b,e);return e}
function Vr(a,b,c){return b?b.map(function(d){return d instanceof Rr?Ur(a,d.key,c,!0):Ur(a,d,c)}):[]}
;var Wr;function Xr(){Wr||(Wr=new Sr);return Wr}
;var Yr=window;function Zr(){var a,b;return"h5vcc"in Yr&&((a=Yr.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Yr.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Yr&&Yr.performance.mark&&Yr.performance.measure?2:0}
function $r(a){var b=Zr();switch(b){case 1:Yr.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Yr.performance.mark(a+"-start");break;case 0:break;default:Xb(b,"unknown trace type")}}
function as(a){var b=Zr();switch(b){case 1:Yr.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Yr.performance.mark(c);Yr.performance.measure(a,b,c);break;case 0:break;default:Xb(b,"unknown trace type")}}
;var bs=U("web_enable_lifecycle_monitoring")&&Zr()!==0,cs=U("web_enable_lifecycle_monitoring");function ds(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?un():d;this.j=c;this.scheduler=d;this.i=new Gi;this.h=a;for(a={cb:0};a.cb<this.h.length;a={jc:void 0,cb:a.cb},a.cb++)a.jc=this.h[a.cb],c=function(e){return function(){e.jc.xc();b.h[e.cb].lc=!0;b.h.every(function(f){return f.lc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.jc),d=this.scheduler.ab(c,d),this.h[a.cb]=Object.assign({},a.jc,{xc:c,
jobId:d})}
function es(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=x(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.lc||(a.scheduler.qa(c.jobId),a.scheduler.ab(c.xc,10))}
ds.prototype.cancel=function(){for(var a=x(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.lc||this.scheduler.qa(b.jobId),b.lc=!0;this.i.resolve()};
ds.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function gs(a){this.state=a;this.plugins=[];this.l=void 0;this.A={};bs&&$r(this.state)}
p=gs.prototype;p.install=function(a){this.plugins.push(a);return this};
p.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
p.transition=function(a,b){var c=this;bs&&as(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(es(this.j),this.j=void 0);hs(this,a,b);this.state=a;bs&&$r(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(is(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function is(a,b){var c=b.filter(function(e){return js(a,e)===10}),d=b.filter(function(e){return js(a,e)!==10});
return a.A.Sg?function(){var e=B.apply(0,arguments);return A(function(f){if(f.h==1)return f.yield(a.Ee.apply(a,[c].concat(la(e))),2);a.ud.apply(a,[d].concat(la(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Fe.apply(a,[c].concat(la(e)));a.ud.apply(a,[d].concat(la(e)))}}
p.Fe=function(a){for(var b=B.apply(1,arguments),c=un(),d=x(a),e=d.next(),f={};!e.done;f={Lb:void 0},e=d.next())f.Lb=e.value,c.Eb(function(g){return function(){ks(g.Lb.name);g.Lb.callback.apply(g.Lb,la(b));ls(g.Lb.name)}}(f))};
p.Ee=function(a){var b=B.apply(1,arguments),c,d,e,f,g;return A(function(h){h.h==1&&(c=un(),d=x(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.B(0);f.tb=e.value;f.Ub=void 0;g=function(k){return function(){ks(k.tb.name);var l=k.tb.callback.apply(k.tb,la(b));typeof(l==null?void 0:l.then)==="function"?k.Ub=l.then(function(){ls(k.tb.name)}):ls(k.tb.name)}}(f);
c.Eb(g);return f.Ub?h.yield(f.Ub,3):h.B(3)}f={tb:void 0,Ub:void 0};e=d.next();return h.B(2)})};
p.ud=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{xc:function(){ks(e.name);e.callback.apply(e,la(b));ls(e.name)},
priority:js(c,e)}});
d.length&&(this.j=new ds(d))};
function js(a,b){var c,d;return(d=(c=a.l)!=null?c:b.priority)!=null?d:0}
function ks(a){bs&&a&&$r(a)}
function ls(a){bs&&a&&as(a)}
function hs(a,b,c){cs&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
fa.Object.defineProperties(gs.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function ms(a){gs.call(this,a===void 0?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.v},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var ns;y(ms,gs);ms.prototype.i=function(a,b){var c=this;this.h=Pm(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
ms.prototype.v=function(a,b){this.h&&(Xi.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function ps(){ns||(ns=new ms);return ns}
;var qs=[];D("yt.logging.transport.getScrapedGelPayloads",function(){return qs});function rs(){this.store={};this.h={}}
rs.prototype.storePayload=function(a,b){a=ss(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
rs.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=ts(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,la(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,la(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,la(this.smartExtractMatchingEntries(a))));return c};
rs.prototype.extractMatchingEntries=function(a){a=ts(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,la(this.store[a[c]])),delete this.store[a[c]]);return b};
rs.prototype.getSequenceCount=function(a){a=ts(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function ts(a,b){var c=ss(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&ss(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(us(b.auth,g[0])){var h=b.isJspb;us(h===void 0?"undefined":h?"true":"false",g[1])&&us(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),us(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function us(a,b){return a===void 0||a==="undefined"?!0:a===b}
rs.prototype.getSequenceCount=rs.prototype.getSequenceCount;rs.prototype.extractMatchingEntries=rs.prototype.extractMatchingEntries;rs.prototype.smartExtractMatchingEntries=rs.prototype.smartExtractMatchingEntries;rs.prototype.storePayload=rs.prototype.storePayload;function ss(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function vs(a,b){if(a)return a[b.name]}
;var ws=Ll("initial_gel_batch_timeout",2E3),xs=Ll("gel_queue_timeout_max_ms",6E4),ys=Math.pow(2,16)-1,zs=Ll("gel_min_batch_size",5),As=void 0;function Bs(){this.l=this.h=this.i=0;this.j=!1}
var Cs=new Bs,Ds=new Bs,Es=new Bs,Fs=new Bs,Gs,Hs=!0,Is=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",Is);var Js={};function Ks(){var a=E("yt.logging.ims");a||(a=new rs,D("yt.logging.ims",a));return a}
function Ls(a,b){if(a.endpoint==="log_event"){Ms();var c=Ns(a),d=Os(a.payload)||"";a:{if(U("enable_web_tiered_gel")){var e=Jq[d||""];var f,g,h,k=Xr().resolve(new Rr(op))==null?void 0:(f=pp())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!U("web_payload_policy_disabled_killswitch"))return;k=Ps(e.tier);if(k===400){Qs(a,b);return}}Js[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};Ks().storePayload(e,a.payload);Rs(b,c,e,d==="gelDebuggingEvent")}}
function Rs(a,b,c,d){function e(){Ss({writeThenSend:!0},U("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=f===void 0?!1:f;d=d===void 0?!1:d;a&&(As=new a);a=Ll("tvhtml5_logging_max_batch_ads_fork")||Ll("web_logging_max_batch")||100;var g=W(),h=Ts(f,c.tier),k=h.l;d&&(h.j=!0);d=0;c&&(d=Ks().getSequenceCount(c));d>=1E3?e():d>=a?Gs||(Gs=Us(function(){e();Gs=void 0},0)):g-k>=10&&(Vs(f,c.tier),h.l=g)}
function Qs(a,b){if(a.endpoint==="log_event"){Ms();var c=Ns(a),d=new Map;d.set(c,[a.payload]);var e=Os(a.payload)||"";b&&(As=new b);return new Wd(function(f,g){As&&As.isReady()?Ws(d,As,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Ns(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);Is[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Ss(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new Wd(function(e,f){var g=Ts(c,d),h=g.j;g.j=!1;Xs(g.i);Xs(g.h);g.h=0;As&&As.isReady()?d===void 0&&U("enable_web_tiered_gel")?Ys(e,f,a,b,c,300,h):Ys(e,f,a,b,c,d,h):(Vs(c,d),e())})}
function Ys(a,b,c,d,e,f,g){var h=As;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=U("enable_web_tiered_gel")?Ks().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Ks().extractMatchingEntries(e),k.set(d,f);else for(d=x(Object.keys(Js)),l=d.next();!l.done;l=d.next())l=l.value,e=U("enable_web_tiered_gel")?Ks().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Ks().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(U("web_fp_via_jspb_and_json")&&c.writeThenSend||!U("web_fp_via_jspb_and_json"))&&delete Js[l];Ws(k,h,a,b,c,!1,g)}
function Vs(a,b){function c(){Ss({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Ts(a,b),e=d===Fs||d===Es?5E3:xs;U("web_gel_timeout_cap")&&!d.h&&(e=Us(function(){c()},e),d.h=e);
Xs(d.i);e=T("LOGGING_BATCH_TIMEOUT",Ll("web_gel_debounce_ms",1E4));U("shorten_initial_gel_batch_timeout")&&Hs&&(e=ws);e=Us(function(){Ll("gel_min_batch_size")>0?Ks().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=zs&&c():c()},e);
d.i=e}
function Ws(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(W()),k=a.size,l=(g===void 0?0:g)&&U("vss_through_gel_video_stats")?"video_stats":"log_event";a=x(a);var n=a.next();for(g={};!n.done;g={Dc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Gc:void 0,Fc:void 0},n=a.next()){var m=x(n.value);n=m.next().value;m=m.next().value;g.batchRequest=Sb({context:vp(b.config_||up())});if(!Qa(m)&&!U("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=m;(m=Is[n])&&
Zs(g.batchRequest,n,m);delete Is[n];g.dangerousLogToVisitorSession=n==="visitorOnlyApprovedKey";$s(g.batchRequest,h,g.dangerousLogToVisitorSession);U("always_send_and_write")&&(e.writeThenSend=!1);g.Gc=function(r){U("start_client_gcf")&&Xi.pa(function(){return A(function(t){return t.yield(at(r),0)})});
k--;k||c()};
g.Dc=0;g.Fc=function(r){return function(){r.Dc++;if(e.bypassNetworkless&&r.Dc===1)try{nq(b,l,r.batchRequest,bt({writeThenSend:!0},r.dangerousLogToVisitorSession,r.Gc,r.Fc,f)),Hs=!1}catch(t){rl(t),d()}k--;k||c()}}(g);
try{nq(b,l,g.batchRequest,bt(e,g.dangerousLogToVisitorSession,g.Gc,g.Fc,f)),Hs=!1}catch(r){rl(r),d()}}}
function bt(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,zg:!!e,headers:{},postBodyFormat:"",postBody:"",compress:U("compress_gel")||U("compress_gel_lr")};ct()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));return a}
function $s(a,b,c){ct()||(a.requestTimeMs=String(b));U("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=T("EVENT_ID"))&&((c=T("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*ys/2)),c++,c>ys&&(c=1),ml("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Zs(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Ms(){var a;(a=E("yt.logging.transport.enableScrapingForTest"))||(a=Kl("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(qs=[],D("yt.logging.transport.enableScrapingForTest",!0),D("yt.logging.transport.scrapedPayloadsForTesting",qs),D("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),D("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
D("yt.logging.transport.scrapeClientEvent",!0))}
function ct(){return U("use_request_time_ms_header")||U("lr_use_request_time_ms_header")}
function Us(a,b){return U("transport_use_scheduler")===!1?Il(a,b):U("logging_avoid_blocking_during_navigation")||U("lr_logging_avoid_blocking_during_navigation")?Pm(function(){if(ps().currentState==="none")a();else{var c={};ps().install((c.none={callback:a},c))}},b):Pm(a,b)}
function Xs(a){U("transport_use_scheduler")?Xi.qa(a):window.clearTimeout(a)}
function at(a){var b,c,d,e,f,g,h,k,l,n;return A(function(m){return m.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=vs(d,Pk),g=(f=d)==null?void 0:f.hotHashData,h=vs(d,Ok),l=(k=d)==null?void 0:k.coldHashData,(n=Xr().resolve(new Rr(op)))?g?e?m.yield(qp(n,g,e),2):m.yield(qp(n,g),2):m.B(2):m.return()):l?h?m.yield(rp(n,l,h),0):m.yield(rp(n,l),0):m.B(0)})}
function Ts(a,b){b=b===void 0?200:b;return a?b===300?Fs:Ds:b===300?Es:Cs}
function Os(a){a=Object.keys(a);a=x(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,Jq[b])return b}
function Ps(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var dt=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",dt);
function et(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||W());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=Er();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!U("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,dt[b]=b in dt?dt[b]+1:0,a.sequence={index:dt[b],groupKey:b},d.endOfSequence&&delete dt[d.sequenceGroup]);(d.sendIsolatedPayload?Qs:Ls)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function En(a,b,c){c=c===void 0?{}:c;var d=lr;T("ytLoggingEventsDefaultDisabled",!1)&&lr===lr&&(d=null);U("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=Er(),c.timestamp=W());et(a,b,d,c)}
;D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var ft=new Set,gt=0,ht=0,jt=0,kt=[],lt=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Dn(a){mt(a)}
function nt(a){mt(a,"WARNING")}
function ot(a){a instanceof Error?mt(a):(a=Ra(a)?JSON.stringify(a):String(a),a=new V(a),a.name="RejectedPromiseError",nt(a))}
function mt(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||T("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||T("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),U("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(gt>=5))){d=kt;var k=fc(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var n=l.split("\n");n.shift();l=n.join("\n")}n=k.lineNumber||"Not available";k=k.fileName||"Not available";var m=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var r=0;r<a.args.length&&!(m=lm(a.args[r],"params."+r,c,m),
m>=500);r++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(r in t){if(t[r]){var v="params."+r,u=nm(t[r]);c[v]=u;m+=v.length+u.length;if(m>500)break}}else c.params=nm(t)}if(d.length)for(r=0;r<d.length&&!(m=lm(d[r],"params.context."+r,c,m),m>=500);r++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);r={message:e,name:f,lineNumber:n,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(r.lineNumber=
r.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=hm();c=x(a.Va);for(d=c.next();!d.done;d=c.next())if(d=d.value,r.message&&r.message.match(d.Kg)){a=d.weight;break a}a=x(a.Sa);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(r)){a=c.weight;break a}a=1}r.sampleWeight=a;a=x(cm);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.ic[r.name])for(e=x(c.ic[r.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=r.message.match(f.regexp)){r.params["params.error.original"]=d[0];e=f.groups;f={};
for(n=0;n<e.length;n++)f[e[n]]=d[n+1],r.params["params.error."+e[n]]=d[n+1];r.message=c.Bc(f);break}r.params||(r.params={});a=hm();r.params["params.errorServiceSignature"]="msg="+a.Va.length+"&cb="+a.Sa.length;r.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(r.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));ib("sample").constructor!==gb&&(r.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(r);
if(r.sampleWeight!==0&&!ft.has(r.message)){if(g&&U("web_enable_error_204"))pt(b===void 0?"ERROR":b,r);else{b=b===void 0?"ERROR":b;b==="ERROR"?(im.Ya("handleError",r),U("record_app_crashed_web")&&jt===0&&r.sampleWeight===1&&(jt++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},U("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:r.message}}}}),En("appCrashed",g)),ht++):b==="WARNING"&&im.Ya("handleWarning",r);if(U("kevlar_gel_error_routing")){g=b;h=h===
void 0?{}:h;b:{a=x(lt);for(c=a.next();!c.done;c=a.next())if(Kn(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:r.stack};r.fileName&&(c.filename=r.fileName);a=r.lineNumber&&r.lineNumber.split?r.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:r.message,errorClassName:r.name,
sampleWeight:r.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];T("FEXP_EXPERIMENTS")&&(h.experimentIds=T("FEXP_EXPERIMENTS"));d=T("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!nl("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=x(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=r.params)for(e=x(Object.keys(d)),
f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=T("SERVER_NAME");e=T("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(En("clientError",h),(g==="ERROR"||U("errors_flush_gel_always_killswitch"))&&Ss(void 0,void 0,!1))}U("suppress_error_204_logging")||pt(b,r)}try{ft.add(r.message)}catch(z){}gt++}}}
function pt(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:T("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=x(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=T("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=x(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=T("SERVER_NAME");b=T("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Ul(T("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function qt(){this.register=new Map}
function rt(a){a=x(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Ng("ABORTED")}
qt.prototype.clear=function(){rt(this);this.register.clear()};
var st=new qt;var tt=Date.now().toString();
function ut(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(tt)for(a=1,b=0;b<tt.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^tt.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var vt,wt=C.ytLoggingDocDocumentNonce_;wt||(wt=ut(),D("ytLoggingDocDocumentNonce_",wt));vt=wt;function xt(a){this.h=a}
p=xt.prototype;p.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
p.getAsJspb=function(){var a=new Wk;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&K(a,2,Lf(this.h.veType)),this.h.veCounter!==void 0&&K(a,6,Lf(this.h.veCounter)),this.h.elementIndex!==void 0&&K(a,3,Lf(this.h.elementIndex)),this.h.isCounterfactual&&K(a,5,Hf(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();Cg(a,Wk,7,b)}this.h.youtubeData!==void 0&&Cg(a,Qk,8,this.h.jspbYoutubeData);return a};
p.toString=function(){return JSON.stringify(this.getAsJson())};
p.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
p.getLoggingDirectives=function(){return this.h.loggingDirectives};function zt(a){return T("client-screen-nonce-store",{})[a===void 0?0:a]}
function At(a,b){b=b===void 0?0:b;var c=T("client-screen-nonce-store");c||(c={},ml("client-screen-nonce-store",c));c[b]=a}
function Bt(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Ct(a){return T(Bt(a===void 0?0:a))}
D("yt_logging_screen.getRootVeType",Ct);function Dt(){var a=T("csn-to-ctt-auth-info");a||(a={},ml("csn-to-ctt-auth-info",a));return a}
function Et(){return Object.values(T("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function Ft(a){a=zt(a===void 0?0:a);if(!a&&!T("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",Ft);function Gt(a,b,c){var d=Dt();(c=Ft(c))&&delete d[c];b&&(d[a]=b)}
function Ht(a){return Dt()[a]}
D("yt_logging_screen.getCttAuthInfo",Ht);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==zt(c)||b!==T(Bt(c)))if(Gt(a,d,c),At(a,c),ml(Bt(c),b),b=function(){setTimeout(function(){a&&En("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:vt,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function It(){var a=Rb(Jt),b;return(new Wd(function(c,d){a.onSuccess=function(e){Hl(e)?c(new Kt(e)):d(new Lt("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Lt("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Lt("Request timed out","net.timeout",e))};
b=Ul("//googleads.g.doubleclick.net/pagead/id",a)})).oc(function(c){if(c instanceof ce){var d;
(d=b)==null||d.abort()}return ae(c)})}
function Lt(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
y(Lt,bb);function Kt(a){this.xhr=a}
;function Mt(){this.h=0;this.i=null}
Mt.prototype.then=function(a,b,c){return this.h===1&&a?(a=a.call(c,this.i))&&typeof a.then==="function"?a:Nt(a):this.h===2&&b?(a=b.call(c,this.i))&&typeof a.then==="function"?a:Ot(a):this};
Mt.prototype.getValue=function(){return this.i};
Mt.prototype.isRejected=function(){return this.h==2};
Mt.prototype.$goog_Thenable=!0;function Ot(a){var b=new Mt;a=a===void 0?null:a;b.h=2;b.i=a===void 0?null:a;return b}
function Nt(a){var b=new Mt;a=a===void 0?null:a;b.h=1;b.i=a===void 0?null:a;return b}
;function Pt(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:Cl(a)?"same-origin":"cors",credentials:Cl(a)?"same-origin":"include"};b={};for(var d=x(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Qt(){return uh()||(Fe||Ge)&&Kn("applewebkit")&&!Kn("version")&&(!Kn("safari")||Kn("gsa/"))||ad&&Kn("version/")?!0:T("EOM_VISITOR_DATA")?!1:!0}
;function Rt(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Uk)if(Uk[d]==c.embeddedPlayerMode){b=Uk[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function St(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Tt;this.isTimeout=a instanceof Lt&&a.errorCode=="net.timeout";this.isCanceled=a instanceof ce}
y(St,bb);St.prototype.name="BiscottiError";function Tt(){bb.call(this,"Biscotti ID is missing from server")}
y(Tt,bb);Tt.prototype.name="BiscottiMissingError";var Jt={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Ut=null;function Vt(){if(U("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Qt())return Error("User has not consented - not fetching biscotti id.");var a=T("PLAYER_VARS",{});if(Pb(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Rt(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function fl(){var a=Vt();if(a!==void 0)return ae(a);Ut||(Ut=It().then(Wt).oc(function(b){return Xt(2,b)}));
return Ut}
function Wt(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Tt;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Tt;a=a.id;gl(a);Ut=Nt(a);Yt(18E5,2);return a}
function Xt(a,b){b=new St(b);gl("");Ut=Ot(b);a>0&&Yt(12E4,a-1);throw b;}
function Yt(a,b){Il(function(){It().then(Wt,function(c){return Xt(b,c)}).oc(Dd)},a)}
function Zt(){try{var a=E("yt.ads.biscotti.getId_");return a?a():fl()}catch(b){return ae(b)}}
;var Bb=ja(["data-"]);function $t(a){a&&(a.dataset?a.dataset[au()]="true":Wb(a))}
function bu(a){return a?a.dataset?a.dataset[au()]:a.getAttribute("data-loaded"):null}
var cu={};function au(){return cu.loaded||(cu.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function du(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||Rb(b);this.assets=a.assets||{};this.attrs=a.attrs||Rb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
du.prototype.clone=function(){var a=new du,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];Pa(c)=="object"?a[b]=Rb(c):a[b]=c}return a};var eu=["share/get_share_panel"],fu=["share/get_web_player_share_panel"],gu=["feedback"],hu=["notification/modify_channel_preference"],iu=["browse/edit_playlist"],ju=["subscription/subscribe"],ku=["subscription/unsubscribe"];var lu=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",lu);function mu(a){hl(lu,arguments)}
;function nu(a,b,c){ou(a,b,c===void 0?null:c)}
function pu(a){a=qu(a);var b=document.getElementById(a);b&&(Nr(a),b.parentNode.removeChild(b))}
function ru(a,b){a&&b&&(a=""+Sa(b),(a=su[a])&&Lr(a))}
function ou(a,b,c){c=c===void 0?null:c;var d=qu(a),e=document.getElementById(d),f=e&&bu(e),g=e&&!f;f?b&&b():(b&&(f=Jr(d,b),b=""+Sa(b),su[b]=f),g||(e=tu(a,d,function(){bu(e)||($t(e),Mr(d),Il(function(){Nr(d)},0))},c)))}
function tu(a,b,c,d){d=d===void 0?null:d;var e=Id("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);dc(e,Mk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function qu(a){var b=document.createElement("a");zb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var su={};function uu(a){var b=vu(a),c=document.getElementById(b),d=c&&bu(c);d||c&&!d||(c=wu(a,b,function(){if(!bu(c)){$t(c);Mr(b);var e=Ya(Nr,b);Il(e,0)}}))}
function wu(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Mk(a);Zb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function vu(a){var b=Id("A");zb(b,new sb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function xu(a){var b=B.apply(1,arguments);if(!yu(a)||b.some(function(d){return!yu(d)}))throw Error("Only objects may be merged.");
b=x(b);for(var c=b.next();!c.done;c=b.next())zu(a,c.value)}
function zu(a,b){for(var c in b)if(yu(b[c])){if(c in a&&!yu(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});zu(a[c],b[c])}else if(Au(b[c])){if(c in a&&!Au(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Bu(a[c],b[c])}else a[c]=b[c];return a}
function Bu(a,b){b=x(b);for(var c=b.next();!c.done;c=b.next())c=c.value,yu(c)?a.push(zu({},c)):Au(c)?a.push(Bu([],c)):a.push(c);return a}
function yu(a){return typeof a==="object"&&!Array.isArray(a)}
function Au(a){return typeof a==="object"&&Array.isArray(a)}
;function Cu(a){a=a===void 0?!1:a;G.call(this);this.h=new M(a);Ec(this,this.h)}
$a(Cu,G);Cu.prototype.subscribe=function(a,b,c){return this.V?0:this.h.subscribe(a,b,c)};
Cu.prototype.unsubscribe=function(a,b,c){return this.V?!1:this.h.unsubscribe(a,b,c)};
Cu.prototype.l=function(a,b){this.V||this.h.Ya.apply(this.h,arguments)};var Du="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function Eu(a,b){var c=c===void 0?!0:c;var d=T("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=oc(window.location.href);e&&d.push(e);e=oc(a);if(Cb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),zb(d,a),a=d.href)if(a=pc(a),a=qc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Ft()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&Fu(a,b,f)}else Fu(a,b)}
function Fu(a,b,c){a=Gu(a);b=b?sc(b):"";c=c||5;Qt()&&um(a,b,c)}
function Gu(a){for(var b=x(Du),c=b.next();!c.done;c=b.next())a=xc(a,c.value);return"ST-"+kc(a).toString(36)}
;function Hu(a){zp.call(this,1,arguments);this.csn=a}
y(Hu,zp);var Ip=new Ap("screen-created",Hu),Iu=[],Ju=0,Ku=new Map,Lu=new Map,Mu=new Map;
function Nu(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Ou({cttAuthInfo:Ht(b)||void 0},b),g=x(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(Nb(k)||!k.trackingParams&&!k.veType)&&nt(Error("Child VE logged with no data"));if(U("no_client_ve_attach_unless_shown")){var l=Pu(h,b);if(k.veType&&!Lu.has(l)&&!Mu.has(l)&&!e){if(!U("il_attach_cache_limit")||Ku.size<1E3){Ku.set(l,[a,b,c,h]);return}U("il_attach_cache_limit")&&Ku.size>1E3&&nt(new V("IL Attach cache exceeded limit"))}h=Pu(c,b);Ku.has(h)?
Qu(c,b):Mu.set(h,!0)}}d=d.filter(function(n){n.csn!==b?(n.csn=b,n=!0):n=!1;return n});
c={csn:b,parentVe:c.getAsJson(),childVes:Fb(d,function(n){return n.getAsJson()})};
b==="UNDEFINED_CSN"?Ru("visualElementAttached",f,c):a?et("visualElementAttached",c,a,f):En("visualElementAttached",c,f)}
function Ru(a,b,c){Iu.push({we:a,payload:c,Gg:void 0,options:b});Ju||(Ju=Jp())}
function Kp(a){if(Iu){for(var b=x(Iu),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,En(c.we,c.payload,c.options));Iu.length=0}Ju=0}
function Pu(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Qu(a,b){a=Pu(a,b);Ku.has(a)&&(b=Ku.get(a)||[],Nu(b[0],b[1],b[2],[b[3]],!0),Ku.delete(a))}
function Ou(a,b){U("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Su(){try{return!!self.localStorage}catch(a){return!1}}
;function Tu(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Uu(a){if(Su()){var b=Object.keys(window.localStorage);b=x(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Tu(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Vu(){if(!Su())return!1;var a=Nm(),b=Object.keys(window.localStorage);b=x(b);for(var c=b.next();!c.done;c=b.next())if(c=Tu(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Wu(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(T("INNERTUBE_CLIENT_NAME")==="WEB"||T("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Xu(a){if(T("LOGGED_IN",!0)&&Wu()){var b=T("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=oc(window.location.href);c&&b.push(c);c=oc(a);Cb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=pc(a),(b=qc(b))?(b=Gu(b),b=(b=wm(b)||null)?zl(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Wu()?(d||(d=T("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&Eu(a,b)}}
;function Yu(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=T("EVENT_ID");d&&(b.ei||(b.ei=d));b&&Eu(a,b);if(c)return!1;Xu(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;a=tc(a,e);Xu(a);f=a+f;var h=h===void 0?wb:h;a:if(h=h===void 0?wb:h,f instanceof sb)h=f;else{for(a=0;a<h.length;++a)if(b=h[a],b instanceof ub&&b.le(f)){h=new sb(f);break a}h=void 0}g=g.location;h=yb(h||tb);h!==void 0&&(g.href=h);return!0}
;function Zu(a){if(Pb(T("PLAYER_VARS",{}))!="1"){a&&el();try{Zt().then(function(){},function(){}),Il(Zu,18E5)}catch(b){rl(b)}}}
;var $u=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function av(){var a=a===void 0?window.location.href:a;if(U("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=Al(a).theme;return $u.get(b)||null}catch(c){}return null}
;function bv(){this.h={};if(this.i=ym()){var a=wm("CONSISTENCY");a&&cv(this,{encryptedTokenJarContents:a})}}
bv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Oa.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=x(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];cv(this,a)}};
function cv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&um("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var dv=window.location.hostname.split(".").slice(-2).join(".");function ev(){this.j=-1;var a=T("LOCATION_PLAYABILITY_TOKEN");T("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=fv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var gv;function hv(){gv=E("yt.clientLocationService.instance");gv||(gv=new ev,D("yt.clientLocationService.instance",gv));return gv}
p=ev.prototype;
p.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.l||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.l||
this.locationPlayabilityToken};
p.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,T("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=fv(this))&&this.h.set("yt-location-playability-token",a,15552E3):um("YT_CL",JSON.stringify({loctok:a}),15552E3,dv,!0))};
function fv(a){return a.h===void 0?new vn("yt-client-location"):a.h}
p.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=fv(this))&&this.h.remove("yt-location-playability-token"):xm("YT_CL");this.l=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
p.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;T("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
p.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
p.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function iv(a){var b={"Content-Type":"application/json"};T("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=T("EOM_VISITOR_DATA"):T("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=T("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=T("LOGGED_IN",!1);T("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=T("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=T("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=T("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=T("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=T("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;function jv(){this.h={}}
jv.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
jv.prototype.get=function(a){if(this.contains(a))return this.h[a]};
jv.prototype.set=function(a,b){this.h[a]=b};
jv.prototype.remove=function(a){delete this.h[a]};function kv(){this.mappings=new jv}
kv.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
kv.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=Xb(b)}}return a};
new kv;function lv(a){return function(){return new a}}
;var mv={},nv=(mv.WEB_UNPLUGGED="^unplugged/",mv.WEB_UNPLUGGED_ONBOARDING="^unplugged/",mv.WEB_UNPLUGGED_OPS="^unplugged/",mv.WEB_UNPLUGGED_PUBLIC="^unplugged/",mv.WEB_CREATOR="^creator/",mv.WEB_KIDS="^kids/",mv.WEB_EXPERIMENTS="^experiments/",mv.WEB_MUSIC="^music/",mv.WEB_REMIX="^music/",mv.WEB_MUSIC_EMBEDDED_PLAYER="^music/",mv.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",mv);
function ov(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=nv[b];if(c){c=new RegExp(c);for(var d=x(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(nv).forEach(function(g){var h=x(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=x(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function pv(){}
pv.prototype.v=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?tm:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=f===void 0?!1:f;e=e===void 0?!1:e;var g=T("INNERTUBE_CONTEXT");if(g){g=Sb(g);U("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;h.clientName==="MWEB"&&h.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(h.clientFormFactor=T("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=
window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=k===void 0?!1:k;Cm();var l="USER_INTERFACE_THEME_LIGHT";Fm(165)?l="USER_INTERFACE_THEME_DARK":Fm(174)?l="USER_INTERFACE_THEME_LIGHT":!U("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");
k=k?l:av()||l;h.userInterfaceTheme=k;if(!f){if(k=Km())h.connectionType=k;U("web_log_effective_connection_type")&&(k=Lm())&&(g.client.effectiveConnectionType=k)}var n;if(U("web_log_memory_total_kbytes")&&((n=C.navigator)==null?0:n.deviceMemory)){var m;n=(m=C.navigator)==null?void 0:m.deviceMemory;g.client.memoryTotalKbytes=""+n*1E6}U("web_gcf_hashes_innertube")&&(k=sp())&&(m=k.coldConfigData,n=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},m&&(g.client.configInfo.coldConfigData=
m),n&&(g.client.configInfo.coldHashData=n),k&&(g.client.configInfo.hotHashData=k));m=Al(C.location.href);!U("web_populate_internal_geo_killswitch")&&m.internalcountrycode&&(h.internalGeo=m.internalcountrycode);h.clientName==="MWEB"||h.clientName==="WEB"?(h.mainAppWebInfo={graftUrl:C.location.href},U("kevlar_woffle")&&om.h&&(m=om.h,h.mainAppWebInfo.pwaInstallabilityStatus=!m.h&&m.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=pm(),
h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):h.clientName==="TVHTML5"&&(!U("web_lr_app_quality_killswitch")&&(m=T("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:m})),m=T("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:m}));if(!U("web_populate_time_zone_itc_killswitch")){b:{if(typeof Intl!=="undefined")try{var r=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(ea){}r=
void 0}r&&(h.timeZone=r)}(r=T("EXPERIMENTS_TOKEN",""))?h.experimentsToken=r:delete h.experimentsToken;r=Ml();bv.h||(bv.h=new bv);h=bv.h.h;m=[];n=0;for(var t in h)m[n++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:r,consistencyTokenJars:m});!U("web_prequest_context_killswitch")&&(t=T("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=t);r=Cm();t=Fm(58);r=r.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);r&&(g.user.lockedSafetyMode=
!0);U("warm_op_csn_cleanup")?e&&(f=Ft())&&(g.clientScreenNonce=f):!f&&(f=Ft())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;hv().setLocationOnInnerTubeContext(g);try{var v=Dl(),u=v.bid;delete v.bid;g.adSignalsInfo={params:[],bid:u};var z=x(Object.entries(v));for(var F=z.next();!F.done;F=z.next()){var I=x(F.value),O=I.next().value,S=I.next().value;v=O;u=S;d=void 0;(d=g.adSignalsInfo.params)==null||d.push({key:v,value:""+
u})}var da;if(U("add_ifa_to_tvh5_requests")&&((da=g.client)==null?void 0:da.clientName)==="TVHTML5"){var ta=T("INNERTUBE_CONTEXT");ta.adSignalsInfo&&(g.adSignalsInfo.advertisingId=ta.adSignalsInfo.advertisingId,g.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",g.adSignalsInfo.limitAdTracking=ta.adSignalsInfo.limitAdTracking)}}catch(ea){mt(ea)}z=g}else mt(Error("Error: No InnerTubeContext shell provided in ytconfig.")),z={};z={context:z};if(F=this.i(a)){this.h(z,F,b);var P;
b="/youtubei/v1/"+ov(this.j());(F=(P=vs(a.commandMetadata,Sk))==null?void 0:P.apiUrl)&&(b=F);P=b;(b=T("INNERTUBE_HOST_OVERRIDE"))&&(P=String(b)+String(pc(P)));b={};U("web_api_key_killswitch")&&(b.key=T("INNERTUBE_API_KEY"));U("json_condensed_response")&&(b.prettyPrint="false");P=Bl(P,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:P,ib:Pt(P),Oa:z,config:a};a.config.Vb?a.config.Vb.identity=c:a.config.Vb={identity:c};return a}mt(new V("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(pv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function qv(){}
y(qv,pv);function rv(){}
y(rv,qv);rv.prototype.v=function(){return{input:"/getDatasyncIdsEndpoint",ib:Pt("/getDatasyncIdsEndpoint","GET"),Oa:{}}};
rv.prototype.j=function(){return[]};
rv.prototype.i=function(){};
rv.prototype.h=function(){};var sv={},tv=(sv.GET_DATASYNC_IDS=lv(rv),sv);function uv(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function vv(){var a=uv();a.info||(a.info={});return a.info}
function wv(a){a=uv(a);a.metadata||(a.metadata={});return a.metadata}
function xv(a){a=uv(a);a.tick||(a.tick={});return a.tick}
function yv(a){a=uv(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function zv(a){a=yv(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Av(a){var b=uv(a).nonce;b||(b=ut(),uv(a).nonce=b);return b}
;function Bv(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function Cv(a){a=a||"";var b=E("ytcsi.reference");b||(Bv(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=Bv(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},Dv=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
X["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",X["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",X["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",X["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",X["asset.history"]="LATENCY_ACTION_CREATOR_CMS_ASSET_HISTORY",X["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",X["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",X["asset.metadata"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",X["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",X["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",X["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",X["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",X["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",X["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",X["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",
X["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",X["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",X["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",
X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",
X["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",
X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",
X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",X["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",X["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",X["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",X["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",X["owner.asset_groups"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",X["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",X["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",X["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",X["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",X["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",X["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.delivery"]=
"LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",X["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",X["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",X["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",X["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",X["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",X["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",X["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",X["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",
X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",
X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",
X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",
X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]=
"LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",X["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",
X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X);function Ev(a,b){zp.call(this,1,arguments);this.timer=b}
y(Ev,zp);var Fv=new Ap("aft-recorded",Ev);var Gv=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",Gv);function Hv(){this.h=0}
function Iv(){Hv.h||(Hv.h=new Hv);return Hv.h}
Hv.prototype.tick=function(a,b,c,d){Jv(this,"tick_"+a+"_"+b)||En("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Hv.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Jv(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,En("latencyActionInfo",a,{cttAuthInfo:c}))};
Hv.prototype.jspbInfo=function(){};
Hv.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Jv(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,En("latencyActionSpan",a,{cttAuthInfo:c}))};
function Jv(a,b){Gv[b]=Gv[b]||{count:0};var c=Gv[b];c.count++;c.time=W();a.h||(a.h=Pm(function(){var d=W(),e;for(e in Gv)Gv[e]&&d-Gv[e].time>6E4&&delete Gv[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new V("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||nt(c)),!0):!1}
;var Kv=window;function Lv(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Mv(){var a;if(U("csi_use_performance_navigation_timing")||U("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Nv(e.requestStart),e.responseEnd=Nv(e.responseEnd),e.redirectStart=Nv(e.redirectStart),e.redirectEnd=Nv(e.redirectEnd),e.domainLookupEnd=Nv(e.domainLookupEnd),e.connectStart=Nv(e.connectStart),e.connectEnd=
Nv(e.connectEnd),e.responseStart=Nv(e.responseStart),e.secureConnectionStart=Nv(e.secureConnectionStart),e.domainLookupStart=Nv(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=U("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Nv(a){return Math.round(Ov()+a)}
function Ov(){return(U("csi_use_time_origin")||U("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=Kv.performance||Kv.mozPerformance||Kv.msPerformance||Kv.webkitPerformance||new Lv;var Pv=!1,Qv=!1,Rv={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Xa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||Dd,Y);function Sv(a,b){if(!U("web_csi_action_sampling_enabled")||!uv(b).actionDisabled){var c=Cv(b||"");xu(c.info,a);a.loadType&&(c=a.loadType,wv(b).loadType=c);xu(zv(b),a);c=Av(b);b=uv(b).cttAuthInfo;Iv().info(a,c,b)}}
function Tv(){var a,b,c,d;return((d=Xr().resolve(new Rr(op))==null?void 0:(a=pp())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!U("web_csi_action_sampling_enabled")||!uv(c).actionDisabled){var d=Av(c),e;if(e=U("web_csi_debug_sample_enabled")&&d){(Xr().resolve(new Rr(op))==null?0:pp())&&!Qv&&(Qv=!0,Z("gcfl",W(),c));var f,g,h;e=(Xr().resolve(new Rr(op))==null?void 0:(f=pp())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Tv();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=Math.pow(2,47));e=f%1E5%e!==0;uv(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Sv(f,c));uv(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||U("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f-=Y.timeOrigin||Y.timing.navigationStart;try{Y.mark(e,{startTime:f})}catch(k){}}e=Cv(c||"");e.tick[a]=b||W();if(e.callback&&e.callback[a])for(e=x(e.callback[a]),f=e.next();!f.done;f=
e.next())f=f.value,f();e=yv(c);e.gelTicks&&(e.gelTicks[a]=!0);f=xv(c);e=b||W();U("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=uv(c).cttAuthInfo;a==="_start"?(a=Iv(),Jv(a,"baseline_"+d)||En("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):Iv().tick(a,d,b,f);Uv(c);return e}}}
function Vv(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=nr+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Wv(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=x(Object.entries(T("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=x(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Xv(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);$b(window)&&a.setAttribute("nonce",$b(window));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Ov(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Yv(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Eb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Gb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Nv(b.startTime)),Z("wffe",Nv(b.responseEnd)))}
function Zv(a){var b=$v("aft",a);if(b)return b;b=T((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=$v(b[d],a);if(e)return e}return NaN}
function $v(a,b){if(a=xv(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Uv(a){var b=$v("_start",a),c=Zv(a),d=U("enable_cow_info_csi")||!Pv;b&&c&&d&&(Fp(Fv,new Ev(Math.round(c-b),a)),Pv=!0)}
function aw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Hb(a,function(b){return b.name==="first-paint"}))return Nv(a.startTime)}a=Y.timing;
return a.re?Math.max(0,a.re):0}
;function bw(a,b){ql(function(){Cv("").info.actionType=a;b&&ml("TIMING_AFT_KEYS",b);ml("TIMING_ACTION",a);var c=Wv();Object.keys(c).length>0&&Sv(c);c={isNavigation:!0,actionType:Dv[T("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=T("PREVIOUS_ACTION");d&&(c.previousAction=Dv[d]||"LATENCY_ACTION_UNKNOWN");if(d=T("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=T("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=Ft())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Vv();if(d===1||d===-1)c.isVisible=!0;wv();vv();
c.loadType="cold";d=vv();var e=Mv(),f=Ov(),g=T("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!U("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=aw();d>0&&Z("fpt",d);d=Mv();d.isPerformanceNavigationTiming&&Sv({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Ov()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Yv();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Rv)Rv.hasOwnProperty(h)&&(e=Rv[h],
Xv(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=x(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Sv(c);c=yv();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=zv();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(wv().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=xv();e=yv();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,$v(k));else if(U("log_repeated_ytcsi_ticks"))for(f=
x(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=x(h);for(e=h.next();!e.done;e=h.next())d=e.value,xu(c,d),xu(k,d),d=!0;d&&Sv(k)}D("ytglobal.timingready_",!0);k=T("TIMING_ACTION");E("ytglobal.timingready_")&&k&&cw()&&Zv()&&Uv()})()}
function cw(){return ql(function(){return dw()})()}
function ew(a,b,c){ql(Sv)(a,b,c===void 0?!1:c)}
function fw(a,b,c){return ql(Z)(a,b,c)}
function dw(){return ql(function(){return"_start"in xv()})()}
function gw(){ql(function(){var a=Av();requestAnimationFrame(function(){setTimeout(function(){a===Av()&&fw("ol",void 0,void 0)},0)})})()}
var hw=window;hw.ytcsi&&(hw.ytcsi.infoGel=ew,hw.ytcsi.tick=fw);var iw="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),jw=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function kw(a,b,c,d){this.v=a;this.fa=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Rb||(a.Rb={});a.Rb=Object.assign({},tv,a.Rb)}
function lw(a,b,c,d){if(kw.h!==void 0){if(d=kw.h,a=[a!==d.v,b!==d.fa,c!==d.l,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new V("InnerTubeTransportService is already initialized",a);
}else kw.h=new kw(a,b,c,d)}
function mw(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?tm:c;var d=nw(a,b);return d?new Wd(function(e,f){var g,h,k,l,n;return A(function(m){switch(m.h){case 1:return m.yield(d,2);case 2:g=m.i;h=g.v(b,void 0,c);if(!h){f(new V("Error: Failed to build request for command.",b));m.B(0);break}Xu(h.input);l=((k=h.ib)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.l.Xe){var r=h.config,t;r=r==null?void 0:(t=r.Vb)==null?void 0:t.sessionIndex;t=sm(0,{sessionIndex:r});n=Object.assign({},
iv(l),t);m.B(4);break}return m.yield(ow(h.config,l),5);case 5:n=m.i;case 4:e(pw(a,h,n)),m.h=0}})}):ae(new V("Error: No request builder found for command.",b))}
function qw(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.j){d=x(iw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function pw(a,b,c){var d=d===void 0?function(){}:d;
var e,f,g,h,k,l,n,m,r,t,v,u,z,F,I,O,S,da,ta,P,ea,na,La,Ka,Og,Pg,rr,sr,tr;return A(function(ha){switch(ha.h){case 1:ha.B(2);break;case 3:if((e=ha.i)&&!e.isExpired())return ha.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Oa)==null?0:g.context)){ha.B(4);break}h=b.Oa.context;ha.B(5);break;case 5:k=x([]),l=k.next();case 8:if(l.done){ha.B(4);break}n=l.value;return ha.yield(n.Mg(h),9);case 9:l=k.next();ha.B(8);break;case 4:if((m=a.i)==null||!m.Rg(b.input,b.Oa)){ha.B(12);break}return ha.yield(a.i.Ig(b.input,
b.Oa),13);case 13:return r=ha.i,U("kevlar_process_local_innertube_responses_killswitch")||qw(a,r,b),ha.return(r);case 12:return(u=(v=b.config)==null?void 0:v.Pg)&&a.h.has(u)?t=a.h.get(u):(z=JSON.stringify(b.Oa),O=(I=(F=b.ib)==null?void 0:F.headers)!=null?I:{},b.ib=Object.assign({},b.ib,{headers:Object.assign({},O,c)}),S=Object.assign({},b.ib),b.ib.method==="POST"&&(S=Object.assign({},S,{body:z})),((da=b.config)==null?0:da.Ce)&&fw(b.config.Ce),ta=function(){return a.fa.fetch(b.input,S,b.config)},t=
ta(),u&&a.h.set(u,t)),ha.yield(t,14);
case 14:if((P=ha.i)&&"error"in P&&((ea=P)==null?0:(na=ea.error)==null?0:na.details))for(La=P.error.details,Ka=x(La),Og=Ka.next();!Og.done;Og=Ka.next())Pg=Og.value,(rr=Pg["@type"])&&jw.indexOf(rr)>-1&&(delete Pg["@type"],P=Pg);u&&a.h.has(u)&&a.h.delete(u);((sr=b.config)==null?0:sr.De)&&fw(b.config.De);if(P||(tr=a.i)==null||!tr.Ag(b.input,b.Oa)){ha.B(15);break}return ha.yield(a.i.Hg(b.input,b.Oa),16);case 16:P=ha.i;case 15:return qw(a,P,b),d(),ha.return(P||void 0)}})}
function nw(a,b){a:{a=a.v;var c,d=(c=vs(b,Tk))==null?void 0:c.signal;if(d&&a.Rb&&(c=a.Rb[d])){var e=c();break a}var f;if((c=(f=vs(b,Rk))==null?void 0:f.request)&&a.Nd&&(f=a.Nd[c])){e=f();break a}for(e in b)if(a.Tc[e]&&(b=a.Tc[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function ow(a,b){var c,d,e,f;return A(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Vb)==null?void 0:d.sessionIndex;var h=g.yield;var k=sm(0,{sessionIndex:e});if(!(k instanceof Wd)){var l=new Wd(Dd);Xd(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},iv(b),f)))})}
;var rw=new Qr("INNERTUBE_TRANSPORT_TOKEN");function sw(){}
y(sw,qv);sw.prototype.j=function(){return ju};
sw.prototype.i=function(a){return vs(a,dl)||void 0};
sw.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(sw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function tw(){}
y(tw,qv);tw.prototype.j=function(){return ku};
tw.prototype.i=function(a){return vs(a,cl)||void 0};
tw.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(tw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});var uw=new Qr("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function vw(a){this.m=a}
y(vw,qv);vw.prototype.j=function(){return eu};
vw.prototype.i=function(a){return vs(a,Yk)||vs(a,Zk)||vs(a,Xk)};
vw.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.m)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.m.i(b.clientParamIdentifier)}};
vw[Pr]=[uw];function ww(){}
y(ww,qv);ww.prototype.j=function(){return gu};
ww.prototype.i=function(a){return vs(a,Vk)||void 0};
ww.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(ww.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function xw(){}
y(xw,qv);xw.prototype.j=function(){return hu};
xw.prototype.i=function(a){return vs(a,bl)||void 0};
xw.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function yw(){}
y(yw,qv);yw.prototype.j=function(){return iu};
yw.prototype.i=function(a){return vs(a,al)||void 0};
yw.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function zw(){}
y(zw,qv);zw.prototype.j=function(){return fu};
zw.prototype.i=function(a){return vs(a,$k)};
zw.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};function Aw(a,b){var c=B.apply(2,arguments);a=a===void 0?0:a;V.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
y(Aw,V);var Bw=new Qr("NETWORK_SLI_TOKEN");function Cw(a){this.h=a}
Cw.prototype.fetch=function(a,b,c){var d=this,e;return A(function(f){e=Dw(d,a,b);return f.return(fetch(e).then(function(g){return d.handleResponse(g,c)}).catch(function(g){nt(g);
if((c==null?0:c.Td)&&g instanceof Aw&&g.errorType===1)return Promise.reject(g)}))})};
function Dw(a,b,c){if(a.h){var d=mc(nc(5,xc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;U("wug_networking_gzip_request")&&(a=gq(c));return new window.Request(b,a)}
Cw.prototype.handleResponse=function(a,b){var c=a.text().then(function(d){if((b==null?0:b.me)&&a.ok)return Yg(b.me,d);d=d.replace(")]}'","");if((b==null?0:b.Td)&&d)try{var e=JSON.parse(d)}catch(g){throw new Aw(1,"JSON parsing failed after fetch");}var f;return(f=e)!=null?f:JSON.parse(d)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Dg(),c=c.then(function(d){nt(new V("Error: API fetch failed",a.status,a.url,d));return Object.assign({},d,{errorMetadata:{status:a.status}})}));
return c};
Cw[Pr]=[new Rr(Bw)];var Ew=new Qr("NETWORK_MANAGER_TOKEN");var Fw;function Gw(){var a,b,c;return A(function(d){if(d.h==1)return a=Xr().resolve(rw),a?d.yield(mw(a),2):(nt(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return nt(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Bg;return d.return(c)}nt(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function Hw(){var a;return(a=T("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var Iw=C.caches,Jw;function Kw(a){var b=a.indexOf(":");return b===-1?{kd:a}:{kd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Lw(){return A(function(a){if(Jw!==void 0)return a.return(Jw);Jw=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return Aa(d,2),d.yield(Iw.open("test-only"),4);case 4:return d.yield(Iw.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=Ba(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Jw)})}
function Mw(a){var b,c,d,e,f,g,h;A(function(k){if(k.h==1)return k.yield(Lw(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(Iw.keys(),3)}c=k.i;d=x(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Kw(f),h=g.datasyncId,!h||a.includes(h)||b.push(Iw.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(n){return n})}))})}
function Nw(){var a,b,c,d,e,f,g;return A(function(h){if(h.h==1)return h.yield(Lw(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=Nm("cache contains other");return h.yield(Iw.keys(),3)}b=h.i;c=x(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Kw(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Ow(){try{return!!self.sessionStorage}catch(a){return!1}}
;function Pw(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Qw(a){if(Ow()){var b=Object.keys(window.sessionStorage);b=x(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Pw(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function Rw(){if(!Ow())return!1;var a=Nm(),b=Object.keys(window.sessionStorage);b=x(b);for(var c=b.next();!c.done;c=b.next())if(c=Pw(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Sw(){Gw().then(function(a){a&&(Uo(a),Mw(a),Uu(a),Qw(a))})}
function Tw(){var a=new Zq;Xi.pa(function(){var b,c,d,e,f;return A(function(g){switch(g.h){case 1:if(U("ytidb_clear_optimizations_killswitch")){g.B(2);break}b=Nm("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Uo(h);Mw(h);Uu(h);Qw(h);return g.return()}c=Vu();d=Rw();return g.yield(Nw(),3);case 3:return e=g.i,g.yield(Vo(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.va()?Sw():a.h.add("publicytnetworkstatus-online",Sw,!0,void 0,void 0),g.h=0}})})}
;function Uw(){this.state=1;this.h=null}
p=Uw.prototype;p.initialize=function(a,b,c){if(a.program){var d,e=(d=a.interpreterUrl)!=null?d:null;if(a.interpreterSafeScript){var f=a.interpreterSafeScript;f?((f=f.privateDoNotAccessOrElseSafeScriptWrappedValue)?(d=fb(),f=new ac(d?d.createScript(f):f)):f=null,d=f):d=null}else d=(f=a.interpreterScript)!=null?f:null;a.interpreterSafeUrl&&(e=Lk(a.interpreterSafeUrl).toString());Vw(this,d,e,a.program,b,c)}else nt(Error("Cannot initialize botguard without program"))};
function Vw(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,nu(c,function(){window[g]?Ww(a,d,g,e):(a.state=3,pu(c),nt(new V("Unable to load Botguard","from "+c)))},f)):b?(f=Id("SCRIPT"),b instanceof ac?cc(f,b):f.textContent=b,f.nonce=$b(window),document.head.appendChild(f),document.head.removeChild(f),window[g]?Ww(a,d,g,e):(a.state=4,nt(new V("Unable to load Botguard from JS")))):nt(new V("Unable to load VM; no url or JS provided"))}
p.isLoading=function(){return this.state===2};
function Ww(a,b,c,d){a.state=5;try{var e=new Hi({program:b,ae:c,Ae:U("att_web_record_metrics"),Ea:"aGIf"});e.Te.then(function(){a.state=6;d&&d(b)});
a.Jc(e)}catch(f){a.state=7,f instanceof Error&&nt(f)}}
p.invoke=function(a){a=a===void 0?{}:a;return this.Mc()?this.Bd({Uc:a}):null};
p.dispose=function(){this.Jc(null);this.state=8};
p.Mc=function(){return!!this.h};
p.Bd=function(a){return this.h.vd(a)};
p.Jc=function(a){Cc(this.h);this.h=a};var Xw=[],Yw=!1;function Zw(){if(!U("disable_biscotti_fetch_for_ad_blocker_detection")&&!U("disable_biscotti_fetch_entirely_for_all_web_clients")&&Qt()){var a=T("PLAYER_VARS",{});if(Pb(a)!="1"&&!Rt(a)){var b=function(){Yw=!0;"google_ad_status"in window?ml("DCLKSTAT",1):ml("DCLKSTAT",2)};
try{nu("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Xw.push(Xi.pa(function(){if(!(Yw||"google_ad_status"in window)){try{ru("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Yw=!0;ml("DCLKSTAT",3)}},5E3))}}}
function $w(){var a=Number(T("DCLKSTAT",0));return isNaN(a)?0:a}
;function ax(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function bx(){Uw.apply(this,arguments)}
y(bx,Uw);bx.prototype.Jc=function(a){var b;(b=ax())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.vd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
bx.prototype.Mc=function(){return!!ax()};
bx.prototype.Bd=function(a){return ax().bgvmc(a)};function cx(a){gs.call(this,a===void 0?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.H},{from:"document_active",to:"document_disposed",action:this.v},{from:"document_disposed_preventable",to:"document_disposed",action:this.v},{from:"document_disposed_preventable",to:"flush_logs",action:this.m},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.m},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
y(cx,gs);cx.prototype.H=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
cx.prototype.v=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
cx.prototype.m=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
cx.prototype.i=function(){this.h=new Map};function dx(a){gs.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.v},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.m},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.m},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.v},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.v},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
U("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
y(dx,gs);dx.prototype.i=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
dx.prototype.h=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
dx.prototype.v=function(a,b){a(b==null?void 0:b.event)};
dx.prototype.m=function(a,b){a(b==null?void 0:b.event)};function ex(){this.l=new cx;this.v=new dx}
ex.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.v.install(c)})};function fx(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
fx.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=Ft(c===void 0?0:c)){a=this.client;d=new xt({trackingParams:d});var e=void 0;if(U("no_client_ve_attach_unless_shown")){var f=Pu(d,c);Lu.set(f,!0);Qu(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Ou({cttAuthInfo:Ht(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Ru("visualElementGestured",f,d):a?et("visualElementGestured",d,a,f):En("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
fx.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new xt({trackingParams:a}),b,c===void 0?0:c)};
fx.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=d===void 0?0:d;c=Ft(d);a||(a=(a=Ct(d===void 0?0:d))?new xt({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Ou({cttAuthInfo:Ht(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Ru("visualElementStateChanged",d,b):a?et("visualElementStateChanged",b,a,d):En("visualElementStateChanged",b,d))}};
function gx(a,b){if(b===void 0)for(var c=Et(),d=0;d<c.length;d++)c[d]!==void 0&&gx(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Nu(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function hx(){ex.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));U("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));U("web_log_cfg_cee_ks")||Pm(ix)}
y(hx,ex);hx.prototype.j=function(){En("finalPayload",{csn:Ft()})};
hx.prototype.h=function(){rt(st)};
hx.prototype.i=function(){var a=gx;fx.h||(fx.h=new fx);a(fx.h)};
function ix(){var a=T("CLIENT_EXPERIMENT_EVENTS");if(a){var b=Ri();a=x(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&En("genericClientExperimentEvent",{eventType:c});delete ll.CLIENT_EXPERIMENT_EVENTS}}
;function jx(){}
function kx(){var a=E("ytglobal.storage_");a||(a=new jx,D("ytglobal.storage_",a));return a}
jx.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(lx()):d.return()})};
function lx(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",jx);function Cn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
Cn.prototype.Ha=function(a){this.handleError(a)};
Cn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":U("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":U("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":mx(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function mx(a,b){kx().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:nx(c==null?void 0:c.usage),deviceStorageQuotaMbytes:nx(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function nx(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var ox={},px=(ox["api.invalidparam"]=2,ox.auth=150,ox["drm.auth"]=150,ox["heartbeat.net"]=150,ox["heartbeat.servererror"]=150,ox["heartbeat.stop"]=150,ox["html5.unsupportedads"]=5,ox["fmt.noneavailable"]=5,ox["fmt.decode"]=5,ox["fmt.unplayable"]=5,ox["html5.missingapi"]=5,ox["html5.unsupportedlive"]=5,ox["drm.unavailable"]=5,ox["mrm.blocked"]=151,ox["embedder.identity.denied"]=152,ox);var qx=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function rx(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function sx(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=x(qx);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function tx(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function ux(a,b,c){G.call(this);var d=this;this.channel="widget";this.sessionId=this.h=this.commands=this.l=null;this.targetOrigin="*";this.j=c||T("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.i=b||null;this.m=!!a;this.listener=function(e){a:if(!(d.j!=="*"&&e.origin!==d.j||d.i&&e.source!==d.i||typeof e.data!=="string")){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(f==null||d.m&&(d.sessionId&&d.sessionId!==f.id||d.channel&&d.channel!==f.channel))&&f)switch(f.event){case "listening":e.origin!==
"null"&&(d.j=d.targetOrigin=e.origin);d.i=e.source;d.sessionId=f.id;d.h&&(d.h(),d.h=null);break;case "command":d.l&&(!d.commands||Cb(d.commands,f.func)>=0)&&d.l(f.func,f.args,e.origin)}}};
window.addEventListener("message",this.listener)}
y(ux,G);ux.prototype.sendMessage=function(a,b){if(b=b||this.i){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){nt(d)}}};
ux.prototype.U=function(){window.removeEventListener("message",this.listener);G.prototype.U.call(this)};
function vx(){var a=wx;this.l=[];this.isReady=!1;this.v={};this.j=[];this.i=[];this.A=!1;this.m=U("web_player_split_event_bus_iframe");var b=this.h=new ux(!!T("WIDGET_ID_ENFORCE")),c=this.ze.bind(this);b.l=c;b.commands=null;this.h.channel="widget";if(b=T("WIDGET_ID"))this.h.sessionId=b;this.api=a;xx(this,"onReady",this.onReady.bind(this));xx(this,"onVideoProgress",this.Oe.bind(this));xx(this,"onVolumeChange",this.Pe.bind(this));xx(this,"onApiChange",this.He.bind(this));xx(this,"onPlaybackQualityChange",
this.Le.bind(this));xx(this,"onPlaybackRateChange",this.Me.bind(this));xx(this,"onStateChange",this.Ne.bind(this));xx(this,"onWebglSettingsChanged",this.Qe.bind(this));xx(this,"onCaptionsTrackListChanged",this.Ie.bind(this));xx(this,"captionssettingschanged",this.Je.bind(this))}
p=vx.prototype;
p.ze=function(a,b,c){if(a==="addEventListener"&&b)a=b[0],a==="onReady"?this.api.logApiCall(a+" invocation",c):a==="onError"&&this.A&&(this.api.logApiCall(a+" invocation",c,this.errorCode),this.errorCode=void 0),this.api.logApiCall(a+" registration",c),this.v[a]||a==="onReady"||(b=yx(this,a,c),this.i.push({eventType:a,listener:b,origin:c}),this.m?this.api.handleExternalCall("addEventListener",[a,b],c):this.api.addEventListener(a,b),this.v[a]=!0);else if(this.api.isExternalMethodAvailable(a,c)){b=b||
[];if(b.length>0&&rx(a)){var d=b;if(Ra(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=sx(d[0],d[1]!==void 0?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];typeof e==="string"&&(e={mediaContentUrl:e,startSeconds:d[1]!==void 0?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=d[2];break b}d=null}e.videoId=d;e=sx(e);break;case "loadPlaylist":case "cuePlaylist":e=
tx(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);rx(a)&&zx(this,Ax(this))}};
p.Wd=function(){this.isReady=!0;this.sendMessage("initialDelivery",Ax(this));this.sendMessage("onReady");Db(this.l,this.sd,this);this.l=[]};
function zx(a,b){a.sendMessage("infoDelivery",b)}
p.sd=function(a){this.isReady?this.h.sendMessage(a):this.l.push(a)};
p.sendMessage=function(a,b){this.sd({event:a,info:b===void 0?null:b})};
function yx(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
p.onReady=function(){var a=this.h,b=this.Wd.bind(this);a.h=b;a=this.api.getVideoData();if(!a.isPlayable){this.A=!0;a=a.errorCode;var c=c===void 0?5:c;this.errorCode=a?px[a]||c:c;this.sendMessage("onError",this.errorCode.toString())}};
function xx(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function Ax(a){if(!a.api)return null;var b=a.api.getApiInterface();Ib(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substr(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
p.Ne=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());zx(this,a)};
p.Le=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());zx(this,a)};
p.Me=function(a){zx(this,{playbackRate:a})};
p.He=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
p.Pe=function(){zx(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
p.Oe=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());zx(this,a)};
p.Qe=function(){var a={sphericalProperties:this.api.getSphericalProperties()};zx(this,a)};
p.Ie=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};zx(this,a)}};
p.Je=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};zx(this,a)}};
p.dispose=function(){this.h=null;for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.m?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};function Bx(a,b,c){Cu.call(this);this.j=a;this.i=b;this.id=c}
y(Bx,Cu);Bx.prototype.jb=function(a,b){this.V||this.j.jb(this.i,this.id,a,b)};
Bx.prototype.U=function(){this.i=this.j=null;Cu.prototype.U.call(this)};
function Cx(a,b,c){G.call(this);this.h=a;this.origin=c;this.j=wr(Dx,"message",this.i.bind(this));this.connection=new Bx(this,a,b);Ec(this,this.connection)}
y(Cx,G);Cx.prototype.jb=function(a,b,c,d){this.V||a!==this.h||(a={id:b,command:c},d&&(a.data=d),this.h.postMessage(JSON.stringify(a),this.origin))};
Cx.prototype.i=function(a){if(!this.V&&a.origin===this.origin){var b=a.data;if(typeof b==="string"){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.V||c.l("command",b.command,b.data,a.origin)}}}};
Cx.prototype.U=function(){yr(this.j);this.h=null;G.prototype.U.call(this)};
function Ex(a,b,c){G.call(this);this.h={};this.started=!1;this.i=U("web_player_split_event_bus_iframe");this.server=new Cx(Fx,b,c);Ec(this,this.server);this.connection=this.server.connection;this.connection.subscribe("command",this.nd,this);this.api=a;this.start()}
y(Ex,G);p=Ex.prototype;p.start=function(){this.started||this.V||(this.started=!0,this.connection.jb("RECEIVING"))};
p.jb=function(a,b){this.started&&!this.V&&this.connection.jb(a,b)};
p.nd=function(a,b,c){if(this.started&&!this.V){var d=b||{};switch(a){case "addEventListener":typeof d.event==="string"&&this.addListener(d.event,c);break;case "removeEventListener":typeof d.event==="string"&&this.removeListener(d.event,c);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Gx(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Hx(a,c))&&this.jb(a,c))}}};
p.addListener=function(a,b){if(!(a in this.h)){var c=this.Ke.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
p.Ke=function(a,b){this.started&&!this.V&&this.connection.jb(a,Ix(a,b))};
p.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
p.addEventListener=function(a,b,c){this.i?this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
p.removeEventListener=function(a,b,c){this.i?this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function Gx(a,b){switch(a){case "loadVideoById":return a=sx(b),[a];case "cueVideoById":return a=sx(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=tx(b),[a];case "cuePlaylist":return a=tx(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Hx(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function Ix(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
p.U=function(){this.connection.unsubscribe("command",this.nd,this);this.connection=null;for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);G.prototype.U.call(this);delete this.api};
var Dx=window,Fx=window.parent;var Jx=new bx;function Kx(){return Jx.Mc()}
function Lx(a){a=a===void 0?{}:a;return Jx.invoke(a)}
;function Mx(a,b,c,d,e){G.call(this);var f=this;this.A=b;this.webPlayerContextConfig=d;this.pc=e;this.Za=!1;this.api={};this.ia=this.m=null;this.W=new M;this.h={};this.da=this.xa=this.elementId=this.Db=this.config=null;this.ba=!1;this.j=this.H=null;this.Ga={};this.qc=["onReady"];this.lastError=null;this.Tb=NaN;this.P={};this.ga=0;this.i=this.l=a;Ec(this,this.W);Nx(this);c?this.ga=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(Ox(this),Px(this))}
y(Mx,G);p=Mx.prototype;p.getId=function(){return this.A};
p.loadNewVideoConfig=function(a){if(!this.V){this.ga&&(clearTimeout(this.ga),this.ga=0);var b=a||{};b instanceof du||(b=new du(b));this.config=b;this.setConfig(a);Px(this);this.isReady()&&Qx(this)}};
function Ox(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.A,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.A:a.config.attrs.id=a.A);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
p.setConfig=function(a){this.Db=a;this.config=Rx(a);Ox(this);if(!this.xa){var b;this.xa=Sx(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Pi(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Pi(Number(a)||a))};
function Qx(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Tx(a){var b=!0,c=Ux(a);c&&a.config&&(b=c.dataset.version===Vx(a));return b&&!!E("yt.player.Application.create")}
function Px(a){if(!a.V&&!a.ba){var b=Tx(a);if(b&&(Ux(a)?"html5":null)==="html5")a.da="html5",a.isReady()||Wx(a);else if(Xx(a),a.da="html5",b&&a.j&&a.l)a.l.appendChild(a.j),Wx(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Yx(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?Rx(a.config):void 0;d&&d(a.l,e,a.webPlayerContextConfig,a.pc);Wx(a)};
a.ba=!0;b?a.H():(nu(Vx(a),a.H),(b=Zx(a))&&uu(b||""),$x(a)&&!c&&D("yt.player.Application.create",null))}}}
function Ux(a){var b=Hd(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function Wx(a){if(!a.V){var b=Ux(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.ba=!1;if(!Yx(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}ay(a)}else a.Tb=setTimeout(function(){Wx(a)},50)}}
function ay(a){Nx(a);a.Za=!0;var b=Ux(a);if(b){a.m=by(a,b,"addEventListener");a.ia=by(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=by(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.m&&a.m(g,a.h[g]);Qx(a);a.xa&&a.xa(a.api);a.W.Ya("onReady",a.api)}
function by(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new V("PlayerProxy error in method call",{error:f,method:c,playerId:a.A}),e.level="WARNING",e;}}}
function Nx(a){a.Za=!1;if(a.ia)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ia(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.m=null;a.ia=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Db};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
p.isReady=function(){return this.Za};
p.addEventListener=function(a,b){var c=this,d=Sx(this,b);d&&(Cb(this.qc,a)>=0||this.h[a]||(b=cy(this,a),this.m&&this.m(a,b)),this.W.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
p.removeEventListener=function(a,b){this.V||(b=Sx(this,b))&&this.W.unsubscribe(a,b)};
function Sx(a,b){var c=b;if(typeof b==="string"){if(a.Ga[b])return a.Ga[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){throw d=new V("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Ga[b]=c}return c?c:null}
function cy(a,b){function c(d){var e=setTimeout(function(){if(!a.V){try{a.W.Ya(b,d!=null?d:void 0)}catch(h){var f=new V("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.A,data:d,originalStack:h.stack});f.level="WARNING";throw f;}f=a.P;var g=String(e);g in f&&delete f[g]}},0);
Ob(a.P,String(e))}
return a.h[b]=c}
p.getPlayerType=function(){return this.da||(Ux(this)?"html5":null)};
p.getLastError=function(){return this.lastError};
function Xx(a){a.cancel();Nx(a);a.da=null;a.config&&(a.config.loaded=!1);var b=Ux(a);b&&(Tx(a)||!$x(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.l)for(a=a.l;b=a.firstChild;)a.removeChild(b)}
p.cancel=function(){this.H&&ru(Vx(this),this.H);clearTimeout(this.Tb);this.ba=!1};
p.U=function(){Xx(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new V("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Ga=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Db=this.config=this.api=null;delete this.l;delete this.i;G.prototype.U.call(this)};
function $x(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function Vx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Zx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Yx(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function Rx(a){for(var b={},c=x(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?Rb(e):e}return b}
;var dy={},ey="player_uid_"+(Math.random()*1E9>>>0);function fy(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?Hd(c):c;var e=ey+"_"+Sa(c),f=dy[e];if(f&&d)return gy(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Mx(c,e,a,b,void 0);dy[e]=f;f.addOnDisposeCallback(function(){delete dy[f.getId()]});
return f.api}
function gy(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var wx=null,hy=null;
function iy(){gw();var a=Cm(),b=Fm(119),c=window.devicePixelRatio>1;if(document.body&&ej(document.body,"exp-invert-logo"))if(c&&!ej(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!ej(d,"inverted-hdpi")){var e=cj(d);dj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&ej(document.body,"inverted-hdpi")&&fj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Gm(b)||0;d=c?d|67108864:d&-67108865;d===0?delete zm[b]:(c=d.toString(16),zm[b]=c.toString());
c=!0;U("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in zm)zm.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(zm[f])));var f=d.join("&");um(b,f,63072E3,a.i,c)}}
function jy(){ky()}
function ly(){fw("ep_init_pr");ky()}
function ky(){var a=wx.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function my(){wx&&wx.sendAbandonmentPing&&wx.sendAbandonmentPing();T("PL_ATT")&&Jx.dispose();for(var a=Xi,b=0,c=Xw.length;b<c;b++)a.qa(Xw[b]);Xw.length=0;pu("//static.doubleclick.net/instream/ad_status.js");Yw=!1;ml("DCLKSTAT",0);Dc(hy);wx&&(wx.removeEventListener("onVideoDataChange",jy),wx.destroy())}
;D("yt.setConfig",ml);D("yt.config.set",ml);D("yt.setMsg",mu);D("yt.msgs.set",mu);D("yt.logging.errors.log",mt);
D("writeEmbed",function(){var a=T("PLAYER_CONFIG");if(!a){var b=T("PLAYER_VARS");b&&(a={args:b})}Zu(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=T("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);bw("embed",["ol"]);c=Hw();if(!c.serializedForcedExperimentIds){var d=Al(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)&&bw("watch",["pbs","pbu","pbp"]);wx=fy(a,c);wx.addEventListener("onVideoDataChange",jy);wx.addEventListener("onReady",ly);a=T("POST_MESSAGE_ID","player");T("ENABLE_JS_API")?hy=new vx:T("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(hy=new Ex(wx,a,b));Zw();U("ytidb_create_logger_embed_killswitch")||Bn();a={};hx.h||(hx.h=new hx);hx.h.install((a.flush_logs={callback:function(){Ss()}},a));
kr();U("ytidb_clear_embedded_player")&&Xi.pa(function(){var f,g;if(!Fw){var h=Xr();Tr(h,{mc:Ew,yd:Cw});var k={Tc:{feedbackEndpoint:lv(ww),modifyChannelNotificationPreferenceEndpoint:lv(xw),playlistEditEndpoint:lv(yw),shareEntityEndpoint:lv(vw),subscribeEndpoint:lv(sw),unsubscribeEndpoint:lv(tw),webPlayerShareEntityServiceEndpoint:lv(zw)}},l=hv(),n={};l&&(n.client_location=l);f===void 0&&(f=rm());g===void 0&&(g=h.resolve(Ew));lw(k,g,f,n);Tr(h,{mc:rw,zd:kw.h});Fw=h.resolve(rw)}Tw()})});
D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||Kx);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||Lx);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||$w);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Yu);D("yt.util.activity.init",E("yt.util.activity.init")||Br);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||Er);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||Cr);window.addEventListener("load",ql(function(){iy()}));
window.addEventListener("pageshow",ql(function(a){a.persisted||iy()}));
window.addEventListener("pagehide",ql(function(a){U("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?my():a.persisted||my()}));
window.onerror=function(a,b,c,d,e){b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var f=!1,g=nl("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(g[h].src.indexOf("/debug-")>0){f=!0;break}}f&&(f=!1,e?f=!0:(typeof a==="string"?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new V(g),e.name="UnhandledWindowError",e.message=g,
e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?mt(e):nt(e))};
le=ot;window.addEventListener("unhandledrejection",function(a){ot(a.reason)});
Db(T("ERRORS")||[],function(a){mt.apply(null,a)});
ml("ERRORS",[]);}).call(this);
