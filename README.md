#  c s g o - s t a t s 
  ` ` ` js
 c o n s t   c s g o S t a t s   =   r e q u i r e ( ' c s g o - s t a t s ' ) ; 
 
     c s g o S t a t s . l o a d ( {  
             k e y :   ' s t e a m A P I k e y ' ,  
             i d :   ' s t e a m C o m m u n i t y I D '  
         } ) . t h e n ( r   = >   {  
               c o n s o l e . l o g ( r . b o d y . p l a y e r s t a t s . s t a t s )  
         } ) . c a t c h ( e   = >   c o n s o l e ( e ) )```