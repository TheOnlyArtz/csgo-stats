# # #   c s g o - s t a t s  
 A b o u t   t h e   m o d u l e :   c s g o - s t a t s   i s   a   v e r y   s i m p l e   t o    
 u s e   m o d u l e   t o   c o m m u n i c a t e   w i t h   c s g o ' s   A P I   b y   f i l l i n g   2   v e r y   s i m p l e   t o   u n d e r s t a n d   p a r a m e t e r s   t h a t   w i l l   l e t   y o u   g e t   d a t a  
# #  E x a m p l e   ` ` ` js c o n s t   c s g o S t a t s   =   r e q u i r e ( ' c s g o - s t a t s ' ) ; 
 
     c s g o S t a t s . l o a d ( {  
             k e y :   ' s t e a m A P I k e y ' ,  
             i d :   ' s t e a m C o m m u n i t y I D '  
         } ) . t h e n ( r   = >   {  
               c o n s o l e . l o g ( r . b o d y . p l a y e r s t a t s . s t a t s )  
         } ) . c a t c h ( e   = >   c o n s o l e ( e ) ) ```
