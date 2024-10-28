```
class me final
{
public:
  me () = default;

  void
  introduce () const
  {
    __builtin_printf ("\nI like to debug life one breakpoint at a time.\n");
    __builtin_printf ("I specialise in writing code that's as stable as a house of cards in a hurricane.\n");
    __builtin_printf ("My code runs faster than a cheetah on caffeine, but crashes harder than my hopes.\n");
    __builtin_printf ("When I'm not coding, I'm busy calculating the probability of my code working...\n");
    __builtin_printf ("...which is about as likely as finding the sqrt of -1 in the real world.\n");
  }

  ~me () = default;
};

int
main ()
{
  me MEME;

  MEME.introduce ();

  return 0;
}
```
