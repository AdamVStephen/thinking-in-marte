# thinking-in-marte

My first book on the Multi-threaded Application for Real-Time execution (MARTe) framework.

## Background and Credit

MARTe has been developed since the early 2000s by a very creative team of engineers, most 
working in Fusion Energy research.  A starting point to find out more is https://github.com/aneto0/MARTe2

For other MARTe/2 resources see [MARTe2-resources](MARTe2_Resources.md)

## Examples

### LinuxTimer

#### [LinuxTimer_1_1](Examples/LinuxTimer/Configurations/LinuxTimer_1_1.cfg)

A minimal demonstration of the LinuxTimer generating outputs at 1Hz and providing `Counter` and `Time` 
to the console via a Logger.

The [configuration][11C] and [output][11O] are provided.  The [README][11R] in the folder explains how to run it.

[11C]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Configurations/LinuxTimer_1_1.cfg
[11O]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Output/LinuxTimer_1_1.out
[11R]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/README.md

<!--
-Are [relative links][11rel] supported ?

[11rel]: (Examples/LinuxTimer/Configurations/LinuxTimer_1_1.cfg)

The answer is No!
-->

#### [LinuxTimer_1_2](Examples/LinuxTimer/Configurations/LinuxTimer_1_2.cfg)

An expanded demonstration of [1_1](#LinuxTimer_1_1) generating outputs at 1Hz and providing 
`Counter`, `Time`, `AbsoluteTime`, `DeltaTime` and `TrigRephase`
to the console via a Logger.

The [configuration][12C] and [output][12O] are provided.  The [README][12R] in the folder explains how to run it.

[12C]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Configurations/LinuxTimer_1_2.cfg
[12O]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Output/LinuxTimer_1_2.out
[12R]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/README.md


#### [LinuxTimer_1_3](Examples/LinuxTimer/Configurations/LinuxTimer_1_3.cfg)

An expanded demonstration of [1_2](#LinuxTimer_1_2) generating outputs at 1Hz 
in two threads which have a phase offset of 500000 (0.5s).

The [configuration][13C] and [output][13O] are provided.  The [README][13R] in the folder explains how to run it.

[13C]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Configurations/LinuxTimer_1_3.cfg
[13O]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/Output/LinuxTimer_1_3.out
[13R]: https://github.com/AdamVStephen/thinking-in-marte/tree/main/Examples/LinuxTimer/README.md
