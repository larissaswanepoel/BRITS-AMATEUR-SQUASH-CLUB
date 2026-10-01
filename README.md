# Brits Amateur Squash Club

Mobile-first squash club app based on the existing prototype.

## Current prototype
- Ladder with 3-place challenge rule
- One active challenge per player
- 7-day challenge deadline / automatic walkover
- Best-of-5, first to 11 per game
- Automatic ladder movement when challenger wins
- Match history with before/after ladder positions
- Player statistics
- Friendly matches that do not change the ladder
- Admin/player management
- Social events and RSVP
- Afrikaans/English UI
- Persistent local data in standalone browser mode

## Important production step
The current standalone build persists data on the device. For a real club deployment where every phone shares the same live data, connect the existing data adapter to Firebase or Supabase and add authenticated user accounts and server-side security rules.
