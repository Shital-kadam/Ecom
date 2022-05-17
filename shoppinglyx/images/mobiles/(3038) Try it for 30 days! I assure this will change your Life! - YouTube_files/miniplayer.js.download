(function(g){var window=this;'use strict';var N3=function(a){g.W.call(this,{F:"div",K:"ytp-miniplayer-ui"});this.Te=!1;this.player=a;this.P(a,"minimized",this.Zg);this.P(a,"onStateChange",this.tJ)},O3=function(a){g.AJ.call(this,a);
this.j=new N3(this.player);this.j.hide();g.mJ(this.player,this.j.element,4);a.yf()&&(this.load(),g.O(a.getRootNode(),"ytp-player-minimized",!0))};
g.w(N3,g.W);g.h=N3.prototype;
g.h.WG=function(){this.tooltip=new g.JN(this.player,this);g.H(this,this.tooltip);g.mJ(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.Cc=new g.HK(this.player);g.H(this,this.Cc);this.Dh=new g.W({F:"div",K:"ytp-miniplayer-scrim"});g.H(this,this.Dh);this.Dh.xa(this.element);this.P(this.Dh.element,"click",this.zC);var a=new g.W({F:"button",Ba:["ytp-miniplayer-close-button","ytp-button"],S:{"aria-label":"Close"},R:[g.MG()]});g.H(this,a);a.xa(this.Dh.element);this.P(a.element,"click",this.Kj);
a=new g.VZ(this.player,this);g.H(this,a);a.xa(this.Dh.element);this.ir=new g.W({F:"div",K:"ytp-miniplayer-controls"});g.H(this,this.ir);this.ir.xa(this.Dh.element);this.P(this.ir.element,"click",this.zC);var b=new g.W({F:"div",K:"ytp-miniplayer-button-container"});g.H(this,b);b.xa(this.ir.element);a=new g.W({F:"div",K:"ytp-miniplayer-play-button-container"});g.H(this,a);a.xa(this.ir.element);var c=new g.W({F:"div",K:"ytp-miniplayer-button-container"});g.H(this,c);c.xa(this.ir.element);this.sQ=new g.hM(this.player,
this,!1);g.H(this,this.sQ);this.sQ.xa(b.element);b=new g.fM(this.player,this);g.H(this,b);b.xa(a.element);this.nextButton=new g.hM(this.player,this,!0);g.H(this,this.nextButton);this.nextButton.xa(c.element);this.Gh=new g.vN(this.player,this);g.H(this,this.Gh);this.Gh.xa(this.Dh.element);this.vc=new g.rM(this.player,this);g.H(this,this.vc);g.mJ(this.player,this.vc.element,4);this.oC=new g.W({F:"div",K:"ytp-miniplayer-buttons"});g.H(this,this.oC);g.mJ(this.player,this.oC.element,4);a=new g.W({F:"button",
Ba:["ytp-miniplayer-close-button","ytp-button"],S:{"aria-label":"Close"},R:[g.MG()]});g.H(this,a);a.xa(this.oC.element);this.P(a.element,"click",this.Kj);a=new g.W({F:"button",Ba:["ytp-miniplayer-replay-button","ytp-button"],S:{"aria-label":"Close"},R:[g.SG()]});g.H(this,a);a.xa(this.oC.element);this.P(a.element,"click",this.tZ);this.P(this.player,"presentingplayerstatechange",this.Xc);this.P(this.player,"appresize",this.ub);this.P(this.player,"fullscreentoggled",this.ub);this.ub()};
g.h.show=function(){this.xe=new g.cp(this.gs,null,this);this.xe.start();this.Te||(this.WG(),this.Te=!0);0!==this.player.getPlayerState()&&g.W.prototype.show.call(this);this.vc.show();this.player.unloadModule("annotations_module")};
g.h.hide=function(){this.xe&&(this.xe.dispose(),this.xe=void 0);g.W.prototype.hide.call(this);this.player.yf()||(this.Te&&this.vc.hide(),this.player.loadModule("annotations_module"))};
g.h.ea=function(){this.xe&&(this.xe.dispose(),this.xe=void 0);g.W.prototype.ea.call(this)};
g.h.Kj=function(){this.player.stopVideo();this.player.La("onCloseMiniplayer")};
g.h.tZ=function(){this.player.playVideo()};
g.h.zC=function(a){if(a.target===this.Dh.element||a.target===this.ir.element)this.player.T().L("kevlar_miniplayer_play_pause_on_scrim")?g.OF(this.player.vb())?this.player.pauseVideo():this.player.playVideo():this.player.La("onExpandMiniplayer")};
g.h.Zg=function(){g.O(this.player.getRootNode(),"ytp-player-minimized",this.player.yf())};
g.h.Td=function(){this.vc.Qb();this.Gh.Qb()};
g.h.gs=function(){this.Td();this.xe&&this.xe.start()};
g.h.Xc=function(a){g.V(a.state,32)&&this.tooltip.hide()};
g.h.ub=function(){g.HM(this.vc,0,this.player.Va().getPlayerSize().width,!1);g.uM(this.vc)};
g.h.tJ=function(a){this.player.yf()&&(0===a?this.hide():this.show())};
g.h.kc=function(){return this.tooltip};
g.h.Gf=function(){return!1};
g.h.gg=function(){return!1};
g.h.Bj=function(){return!1};
g.h.Az=function(){};
g.h.ap=function(){};
g.h.uu=function(){};
g.h.yp=function(){return null};
g.h.Wx=function(){return null};
g.h.Fk=function(){return new g.im(0,0,0,0)};
g.h.handleGlobalKeyDown=function(){return!1};
g.h.handleGlobalKeyUp=function(){return!1};
g.h.ys=function(a,b,c,d,e){var f=0,k=d=0,l=g.Cm(a);if(b){c=g.kp(b,"ytp-prev-button")||g.kp(b,"ytp-next-button");var m=g.kp(b,"ytp-play-button"),n=g.kp(b,"ytp-miniplayer-expand-watch-page-button");c?f=k=12:m?(b=g.Am(b,this.element),k=b.x,f=b.y-12):n&&(k=g.kp(b,"ytp-miniplayer-button-top-left"),f=g.Am(b,this.element),b=g.Cm(b),k?(k=8,f=f.y+40):(k=f.x-l.width+b.width,f=f.y-20))}else k=c-l.width/2,d=25+(e||0);b=this.player.Va().getPlayerSize().width;e=f+(e||0);l=g.bh(k,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.h.showControls=function(){};
g.h.Hm=function(){};
g.h.Vl=function(){return!1};g.w(O3,g.AJ);O3.prototype.create=function(){};
O3.prototype.aj=function(){return!1};
O3.prototype.load=function(){this.player.hideControls();this.j.show()};
O3.prototype.unload=function(){this.player.showControls();this.j.hide()};g.zJ("miniplayer",O3);})(_yt_player);
