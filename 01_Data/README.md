# Data Structure
Each experiment has a plaintext __.csv__ file that stores the time series data for each sensor for each experiment. The *Time* column, in seconds, in each experiment file is offset based on when heating of the initiating cell began. In other words, negative values represent background data and positive values represent time after the experiment started. The *Timestamp* column represents the local clock time during which the experiment was conducted. This column is used to sync the corresponding **_Events.csv** file to the primary data file for each experiment. The **_Events** file contains the relevant actions performed during the experiments (e.g., ignition, ventilation, suppression, etc.).

## Experiment 1
Experiment 1 was a baseline experiment which did not incorporate any active suppression. The purpose of the experiment was to characterize the thermal and chemical conditions generated during thermal runaway and to assess the efficacy of industrial gas detectors and sensors for identifying thermal runaway and potential deflagration hazards.

## Experiment 2
Experiment 2 utilized a clean agent suppression system which deployed Novec 1230 after two smoke detectors were activated. The purpose of this experiment was to to characterize the thermal and chemical conditions generated after deploying a clean agent into an ESS undergoing thermal runaway and to assess the efficacy of such a suppression system for limiting the propogation of thermal runaway.

## Experiment 3
Experiment 3 utilized a water suppression system designed to simulate an automati sprinkler system installed inside an ESS container. The purpose of this experiment was to to characterize the thermal and chemical conditions generated after water suppression into an ESS undergoing thermal runaway and to assess the efficacy of such a suppression system for limiting the propogation of thermal runaway.