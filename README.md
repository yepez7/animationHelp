# animationHelp
how to set animation

  /**i juust waned to go down and each time the block go down create a new one but i jave some plobles
     * I can dedsplay it do I need to inport something or what im doing wrong.
    */


//  block A
    public class A 
    {
    
    
    
    // this is my image view
                    ImageView pointA = (ImageView) findViewById(R.id.imageView_block_A);
    /**i juust waned to go down and each time the block go down create a new one but i jave some plobles
     * I can dedsplay it do I need to inport something or what im doing wrong.
    */
        ValueAnimatorAnimator blockplay = ObjectAnimator.ofFloat(pointA, "y", 50f);
        blockplay.addListener(new AnimatorListenerAdapter()
         {
    
    
    
    
                 public void onAnimationStart(Animator animation) {
                        int inBlockPlay = 0;
    
                        for( inBlockPlay == 0; inBlockPlay >= 400; inBlockPlay++){
    
                            if(inBlockPlay == 100;)
                            {
    
                                blockplay.addListener(new AnimatorListenerAdapter()
                                {
                                    public void onAnimationRepeat(Animator animation)
                                    {
                                        int inBlockPlay = 0;
                                        for( inBlockPlay == 0; inBlockPlay >= 400; inBlockPlay++) {
                                         ValueAnimatorAnimator blockplay = ObjectAnimator.ofFloat(pointA, "y", 10f);
                                            pointA.startAnimation(blockplay);
                                        }
                                    }
    
                                }
                            }
    
                                    pointA.startAnimation(blockplay);
                }
            }
         }
    }
}


