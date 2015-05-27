# learned_machine
This repo will contain stuff i come up with while figuring out a way to create a big data/machine learning trading prediction tool
For now, the general outlines are these:
1) Decide on the source of data -- check
2) Figure out ways to import data (Flume, Hive, something else)  -- check (although it's pretty lame)
3) Place data into HDFS (probably) -- check
4) Run machine-learning magic on it
5) Come up with predictions
6) Test predictions against reality (probably)
7) Visualise stuff (maybe)

Things I'll probably use are Sparkling Water and other nice thing from the Hadoop stack.

Also, have to figure out the whole trading side of this thing.

Disclaimer: these recipes are an exercise in configuring and teaching a machine. If you follow them, the machine you get will NOT get you rich by magic. I'm not to be held accountable for any losses resulting from using these things. Use at your own risk, and be warned!

Actually, this repo will contain the code that current Apache Mahout lacks that I'll need to build the machine. Logistic regression is there already, now I need SVMs and ANNs (which, in some form, might be there already too).
These would be written in Java, which I don't really know. So this code will probably suck. At first. But then it'll gradually get better - and I'll be able to monitor my progress.
So, on to work.

