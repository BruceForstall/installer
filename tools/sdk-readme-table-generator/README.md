# SDK README table generator

To generate the table of [SDK per check in build download table](https://github.com/dotnet/core-sdk).

Edit the `inputBranches` in Program.fs when there is a new branch created. Run the program, it will generate the table with updated branch. It is not too smart, so if there is new platform added, we need more to change the program. But it is still better than edit it by hand.

I wrote it to learn F#, since it is almost the "99 bottle of beer" kata. Please point out places I can improve if you are interested.
