# Support for Instrument

## Getting in touch

Email **badbatoff@gmail.com**. One person reads it, so a reply may take a few
days. Say which iPhone and which iOS version you are on, and what you were doing
when it went wrong.

Do not send your database or a screenshot showing your own figures unless you
want to. Nothing in it is needed to answer most questions, and the app is built
so that nobody else ever has to see your record.

## Things people ask

**How do I log a session?**
Tap "Add the session text" on the Today screen and type or paste it in plain
text, the
way you would write it in a notebook. Something like `squat 3x5 100kg rpe 8`
works. The app shows you how it read every line before anything is saved, so you
can see whether it understood you.

**Why is the advice empty?**
Every suggestion is built from your own previous session for that lift, so there
has to be one. Log a session and the cards appear at the bottom of the same
sheet.

**Why does the recovery part say nothing?**
Two reasons, and the first one is permanent for some phones. Sleep, heart rate
variability, resting heart rate and breathing rate do not exist on an iPhone
alone, so without a watch or a band that half of the app stays silent and
everything else works as described.

With one, it still waits. It needs seven days of your own figures inside a two
week window, so from a standing start it is about a fortnight before it says
anything. It compares you against your own baseline rather than against a
population, and until there is a baseline there is nothing honest to say. That
wait is deliberate. If you already had a watch before installing, it reads the
history Health has kept and can speak on the first day.

**Health is connected but nothing arrived.**
iOS grants Health permission one data type at a time, and it is easy to grant
some and not others. Open the Health app, go to Sharing, then Apps, then
Instrument, and check each one. The app also tells you on the Today screen when
Health has delivered nothing.

**I bought it on another device and it is not unlocked.**
Tap Restore on the Today screen. The unlock belongs to your Apple ID, so it
restores on any device signed in to the same one.

**What is the difference between the three prices?**
Nothing, except how you pay. All three unlock exactly the same thing. The
monthly plan comes with the first week free and renews until you stop it; the
yearly plan renews once a year and works out at about half the monthly rate;
the one payment is yours for good and never renews. Either subscription can be
cancelled whenever you like, in Settings under your Apple ID, Subscriptions.
Because the two subscriptions are in one group you can move between them
without being charged twice.

**How do I cancel a subscription?**
In iOS Settings, tap your name at the top, then Subscriptions. That is Apple's
screen, not ours; we cannot cancel it for you and cannot see that you have.

**How do I get my data out?**
Open the Files app and look under Instrument. The database is an ordinary SQLite
file. Copy it anywhere.

**How do I delete everything?**
Delete the app. The record is inside it and goes with it. There is no server
copy, because there is no server.

**Can I get a refund?**
Refunds are handled entirely by Apple, at reportaproblem.apple.com. We cannot
issue one and are not told when you ask for one.

**Is my data sent anywhere?**
No. The app makes two network connections and neither carries anything about
you: one to Apple's App Store to handle a purchase, and one, after a report has
opened, asking Apple to show its own rating alert. See the privacy policy.

## Reporting something wrong

If the app read one of your lines incorrectly, that is the most useful thing you
can report. Send the exact line as you typed it and what it should have meant.
The parser is tested against a large set of real lines and yours can be added to
it.

## Not medical advice

Instrument is a training log. What it suggests is not medical advice and not a
diagnosis. Anything that feels like a medical question is one, and belongs with
a clinician. Ask a doctor before beginning to train, particularly if you are
starting out, coming back from an injury or illness, pregnant, or managing a
condition.
