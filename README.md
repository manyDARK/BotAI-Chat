# BotAI-Chat
BotChat in minigames servers 1.2-1.6

- [x] Working in Chat
- [ ] Working in NPC/BOT (Slapper, ect..)

# Messages (60)
---------------------------

         public function onChat(PlayerChatEvent $e){
         $player = $e->getPlayer();
         $talk = $e->getMessage();
         if(strtolower($talk) == "hello"){
         $player->sendMessage("[§dBOT§f] §lHi there :D");
         }
}

         public function onChat2(PlayerChatEvent $e){
         $player = $e->getPlayer();
         $talk = $e->getMessage();
         if(strtolower($talk) == "noob"){
         $player->sendMessage("[§dBOT§f]§l No noobs!");
         }
}

         public function onChat3(PlayerChatEvent $e){
         $talk = $e->getPlayer();
         $player = $e->getMessage();
         if(strtolower($talk) == "this sucks"){
         $player->sendMessage("[§dBOT§f] §lNo it dosen't");
         }
}

         public function onChat4(PlayerChatEvent $e){
         $player = $e->getPlayer();
         $talk = $e->getMessage();
         if(strtolower($talk) == "i won"){
         $player->sendMessage("[§dBOT§f]§l GG! player.");
         }
}

         public function onChat5(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "hacker"){
         $player->sendMessage("[§dBOT§r]§l Hacker? Report them to the server staffs!");
         }
}

         public function onChat6(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "nice"){        
         $player->sendMessage("[§dBOT§r]§l YES! Nice indeed.");
         }
}

         public function onChat7(PlayerChatEvent $e){
         $player = $e->getPlayer();
         $talk = $e->getMessage();
         if(strtolower($talk) == "bot"){
         $player->sendMessage("[§dBOT§r]§l Yes?");
         }
}

         public function onChat8(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "how are you bot"){
         $player->sendMessage("[§dBOT§r] §lIm fine as you think of :D");
         }
}

         public function onChat9(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "hello guys"){
         $player->sendMessage("[§dBOT§r] §lHi there player!");
         }
}

         public function onChat10(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "lol"){
         $player->sendMessage("[§dBOT§r] §lLOL");    
         }    
}

         public function onChat11(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "i love you"){
         $player->sendMessage("[§dBOT§r] §lI love you too XD");    
         }    
}

         public function onChat12(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "i love this server"){
         $player->sendMessage("[§dBOT§r] §lWe also love you for being here");    
         }    
}

         public function onChat13(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "are you pro bot"){
         $player->sendMessage("[§dBOT§r] §lYep. I can kill all slimes only so yep.");    
         }    
}
      
         public function onChat14(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "You are handsome"){
         $player->sendMessage("[§dBOT§r] §lAre you talking to me? xD");    
         }    
}

         public function onChat15(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "im sad"){
         $player->sendMessage("[§dBOT§r] §lwhy are you sad?");    
         }    
}

         public function onChat16(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "gg"){
         $player->sendMessage("[§dBOT§r] §lGoodGame!");    
         }    
}

         public function onChat17(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "yes"){
         $player->sendMessage("[§dBOT§r] §lNo.");    
         }    
}

         public function onChat18(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "no"){
         $player->sendMessage("[§dBOT§r] §lyes");    
         }    
}

         public function onChat19(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "say hi to yt"){
         $player->sendMessage("[§dBOT§r] §lHello yt!!!");    
         }    
}

         public function onChat20(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "who is the best youtuber?"){
         $player->sendMessage("[§dBOT§r] §lDanTDM");    
         }    
}

         public function onChat21(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "im alone"){
         $player->sendMessage("[§dBOT§r] §lNo you're not");    
         }    
}

         public function onChat22(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "lol noob"){
         $player->sendMessage("[§dBOT§r] §lHey you're bullying!");    
         }    
}

         public function onChat23(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "hi bot"){
         $player->sendMessage("[§dBOT§r] §lHello player");    
         }    
}

         public function onChat24(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot kill me!"){
         $player->kill();    
         }    
}

         public function onChat25(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "great"){
         $player->sendMessage("[§dBOT§r] §lsmart");    
         }    
}

         public function onChat26(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "lets collab"){
         $player->sendMessage("[§dBOT§r] §lGreat Idea player");    
         }    
}
 
         public function onChat27(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot kick me"){
         $player->kick();    
         }    
}

         public function onChat28(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "op me"){
         $player->sendMessage("[§dBOT§r] §lLol NO!");    
         }    
}

         public function onChat29(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot noob"){
         $player->sendMessage("[§dBOT§r] §lMaybe you!");    
         }    
}

         public function onChat30(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "****"){
         $player->sendMessage("[§dBOT§r] §lSwearing is bad for you!");    
         }    
}

         public function onChat31(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "this is fun"){
         $player->sendMessage("[§dBOT§r] §lI wish I could have fun too!");    
         }    
}

         public function onChat32(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "beautiful"){
         $player->sendMessage("[§dBOT§r] §lMe?");    
         }    
} 

         public function onChat33(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "i am sick"){
         $player->sendMessage("[§dBOT§r] §lGet well player");    
         }    
} 

         public function onChat34(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "im bored"){
         $player->sendMessage("[§dBOT§r] §lSame");    
         }    
}

         public function onChat35(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bye"){
         $player->sendMessage("[§dBOT§r] §lgoodbye!");    
         }    
} 

         public function onChat36(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot what is your gender?"){
         $player->sendMessage("[§dBOT§r] §lI am a male. Why?");    
         }    
} 

         public function onChat37(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot are you gay?"){
         $player->sendMessage("[§dBOT§r] §lI don't know");    
         }    
}

         public function onChat38(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "kiss me bot"){
         $player->sendMessage("[§dBOT§r] §lNah. I dont like to.");    
         }    
}  

         public function onChat39(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "help me bot"){
         $player->sendMessage("[§dBOT§r] §lUh ok.");    
         }    
}

         public function onChat40(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bots are noobs"){
         $player->sendMessage("[§dBOT§r] §lNo they don't");    
         }    
} 

         public function onChat41(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot 1+1"){
         $player->sendMessage("[§dBOT§r] §lequals 2");    
         }    
}

         public function onChat42(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot 2+2"){
         $player->sendMessage("[§dBOT§r] §lequals 4");    
         }    
}

         public function onChat43(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot op me"){
         $player->sendMessage("[§dBOT§r] §lNope. ^_^");    
         }    
}

         public function onChat44(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "its empty"){
         $player->sendMessage("[§dBOT§r] §lNo its not");    
         }    
}

         public function onChat45(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot what is your favorite show?"){
         $player->sendMessage("[§dBOT§r] §lwatching zZPROGAMERZz423");    
         }    
}

         public function onChat46(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "talk to me bot"){
         $player->sendMessage("[§dBOT§r] §lOkay.");    
         }    
}     

         public function onChat47(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot can you kick me?"){
         $player->kick();    
         }    
}

         public function onChat48(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "your pretty"){
         $player->sendMessage("[§dBOT§r] §lAre you talking to me?");    
         }    
}

         public function onChat49(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "how do i play skywars?"){
         $player->sendMessage("[§dBOT§r] §lpress the sw sign");    
         }    
}

         public function onChat50(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "this server sucks"){
         $player->sendMessage("[§dBOT§r] §lNo it dosen't!!!");    
         }    
}

         public function onChat51(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "i dont have friends"){
         $player->sendMessage("[§dBOT§r] §lI can be");    
         }    
}

         public function onChat52(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot!"){
         $player->sendMessage("[§dBOT§r] §lWhat!?");    
         }    
} 
    
         public function onChat53(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "nothing bot"){
         $player->sendMessage("[§dBOT§r] §lreally? -_-");    
         }    
} 

         public function onChat54(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "im stuck"){
         $player->sendMessage("[§dBOT§r] §ldo /hub instead or say kill me bot lol");    
         }    
}  
          
         public function onChat55(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "who is the best"){
         $player->sendMessage("[§dBOT§r] §lMEEEE!");    
         }    
}

         public function onChat56(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot can i ask you a question"){
         $player->sendMessage("[§dBOT§r] §lSure player!");    
         }    
}    

         public function onChat57(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "bot how old are you"){
         $player->sendMessage("[§dBOT§r] §l23.");    
         }    
}                                                                                               
  
         public function onChat58(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "join my server"){
         $player->sendMessage("[§dBOT§r] §lNo advertising!!");    
         }    
}

         public function onChat59(PlayerChatEvent $e){
         $talk = $e->getMessage();
         $player = $e->getPlayer();
         if(strtolower($talk) == "can i apply"){
         $player->sendMessage("[§dBOT§r] §lthen apply");    
         }    
} 
        
         public function onChat60(PlayerChatEvent $e){
         $player = $e->getPlayer();
         $talk = $e->getMessage();
         if(strtolower($talk) == "***"){
         $player->sendMessage("[§dBOT§r] §lDon't say that!");
         }
