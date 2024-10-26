```
class me final
{
public:
  me ()
  {
    __builtin_printf ("I was born... and with, it my hopes of finishing my projects vanished faster than a local variable.\n");
  }

  void
  introduce () const
  {
    __builtin_printf ("\nI like to debug life one breakpoint at a time.\n");
    __builtin_printf ("I specialise in writing code that's as stable as a house of cards in a hurricane.\n");
    __builtin_printf ("My code runs faster than a cheetah on caffeine, but crashes harder than my hopes.\n");
    __builtin_printf ("When I'm not coding, I'm busy calculating the probability of my code working...\n");
    __builtin_printf ("...which is about as likely as finding the sqrt of -1 in the real world.\n");
  }

  ~me ()
  {
    __builtin_printf ("\nThen I died, just like my previous projects, leaving behind a trail of memory leaks.\n");
  }
};

int
main ()
{
  me MEME;

  MEME.introduce ();

  return 0;
}
```
