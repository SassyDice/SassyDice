while(noSuccess)
{
        tryAgain();
        
        if(Alive)
        {
                eat();
                code();
                sleep();
                repeat();
        }
        else if(Dead)
                break();
}
