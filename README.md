e x t e n d . j s  
 = = = = = = = = =  
  
 E x t e n d J S   e x t e n d s   J a v a S c r i p t   w i t h   a   s i m p l e   y e t   p o w e r f u l   c l a s s   a b s t r a c t i o n .  
  
 I n f o   a n d   e x a m p l e s   a t   h t t p : / / e x t e n d j s . o r g  
  
 F A Q :  
 - - - - - - - - - - - - - - - - - - - - - - - - -  
 < d l >  
 < d t > J a v a S c r i p t   h a s   g r e a t   p r o t o t y p i c a l   c l a s s   i n h e r i t a n c e ,   s o   w h y   w r i t e   t h i s ? < / d t >  
 < d d >  
 W h i l e   w r i t i n g ,   a   y e t   t o   b e   r e l e a s e d   H T M L 5   g a m e   e n g i n e ,   I   f e l t   a   n e e d   f o r   a   b e t t e r   w a y   t o   r e - u s e   a n d   e x t e n d   b a s i c   p r i m i t i v e s .   O v e r   t h e   p a s t   y e a r s   I   a l s o   s p e n d   a   l a r g e   a m o u n t s   o f   t i m e   w o r k i n g   w i t h   C #   a n d   A c t i o n S c r i p t   3   a n d   I   r e a l l y   m i s s e d   t h e   m o r e   p o w e r f u l   c l a s s   s y s t e m   f r o m   t h o s e   l a n g u a g e s .  
 < / d d >  
 < d d >  
 E x t e n d J S   s t a r t e d   o u t   a s   a   s i m p l e   s c o p e   h a c k ,   a l l o w i n g   f o r   c o d e   e x e c u t i o n   d u r i n g   p r o t o t y p i c a l   c l a s s   i n s t a n t i a t i o n .   F r o m   t h e r e   i t   w a s   t r i v i a l   t o   a d d   m e t h o d   a n d   v a l u e   c o p y i n g   a n d   o v e r l o a d i n g   a n d   t h e   p r o j e c t   t o o k   o f   f r o m   t h e r e .  
 < / d d >  
 < d d >  
 F o r   m o r e   t h a n   a   y e a r   I   r e v i s i t e d   t h e   p r o j e c t   m u l t i p l e   t i m e s ,   f i x i n g   b u g s   a n d   m a k i n g   t h e   s y n t a x   s i m p l e r .   T h e   v e r s i o n   e x i s t i n g   t o d a y   i s   f a r   f r o m   t h e   o r i g i n a l   v e r s i o n   a n d   I   m u s t   h a v e   r e w r i t t e n   i t   m o r e   t h a n   f i v e   t i m e s   f r o m   s c r a t c h   i n   a n   a t t e m p t   t o   s i m p l i f y   a n d   r e s o l v e   i s s u e s .      
 < / d d >  
 < d t > I   s t i l l   d o n ' t   u n d e r s t a n d   w h y   J a v a S c r i p t   n e e d s   t h i s ? < / d t >  
 < d d > G r a n t e d ,   b y   i t s e l f   E x t e n d J S   d o e s   n o t   d o   m u c h ,   h o w e v e r   i t ' s   a   g r e a t   b a s e   o n   w h i c h   t o   b u i l d   l a r g e r ,   J a v a S c r i p t   h e a v y ,   p r o j e c t s   s u c h   a s   g a m e s   a n d   w e b   a p p l i c a t i o n s . < / d d >  
  
 < d t > Y o u   a r e   u s i n g   t h e   r e s e r v e d   w o r d   s u p e r   i n   y o u r   c o d e   a n d   i t   w o n ' t   r u n   i n   o l d e r   b r o w s e r s ! < / d t >  
 < d d > N e i t h e r   w i l l   t h e   H T M L 5   g a m e   e n g i n e   I   a m   w o r k i n g   o n   a n d   I   a m   p e r f e c t l y   h a p p y   w i t h   t h i s   c h o i c e .   D o   a   s e a r c h   r e p l a c e   f o r   s u p e r   t o   s u p   a n d   i t   w i l l   h a p p i l y   r u n   i n   I E 6 . < / d d >  
  
 < d t > I   t r i e d   r u n n i n g   i t   i n   s t r i c t   m o d e ,   i t   d o e s   n o t   w o r k . < / d t >  
 < d d > T h e   c o d e   r e l i e s   o n   a r g u m e n t s . c a l l e e   a s   p a r t   o f   i n h e r i t a n c e ,   I   s a d l y   s e e   n o   p r e t t y   w a y   t o   f i x   t h i s .   S u g g e s t i o n s   a r e   w e l c o m e ! < / d d >  
  
 < d t > I   d o n ' t   l i k e   h o w   i t   a u t o m a t i c a l l y   a d d s   c l a s s e s   t o   t h e   g l o b a l   s c o p e . < / d t >  
 < d d > A   s i m p l e   d e s i g n   c h o i c e ,   i f   y o u   u p d a t e   t h e   c l a s s   t o   r e t u r n   c h i l d   y o u   c a n   a s s i g n   t h e   c l a s s e s   h o w e v e r   y o u   l i k e . < / d d >  
  
 < d t > Y o u r   C D N   i s   u s e l e s s ,   i t   d o e s   n o t   e v e n   s u p p o r t   H T T P S ! < / d t >  
 < d d > I   a m   a w a r e ;   I   h a v e   y e t   t o   c o l l e c t   t h e   c o m m u n i t y   s u p p o r t   t o   p u t   i t   o n   C D N J S .   S t a y   t u n e d   f o r   u p d a t e s . < / d d >  
 < / d l > 