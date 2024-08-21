# SCADA Project

## Description

This project is a SCADA (Supervisory Control and Data Acquisition) system designed to monitor and control  tank level management using _Siemens TIA Portal_. 
The project includes various components and configurations to ensure efficient and reliable operation.

## Project Structure

The project is organized into the following directories:

- **AdditionalFiles/PLCM**: Contains the `plcmArchive.pma` file.
- **IM/HMI/C/0**: Contains runtime data files and generated files such as `~RtData.1`, `~RtData.2`, `Generates/`, `intermediate.dti`, `RtData.idx`, and `RtData.plf`.
- **IM/SearchIndex**: Contains search index files like `_a_1.del`, `_a.cfs`, `_b_1.del`, `_b.cfs`, `_d.cfs`, `_e.cfs`, `segments_3kq`, `segments_3kr`, and `segments.gen`.
- **IM/SPL**: Contains the `options` file.
- **Logs**: Directory for log files.
- **SCADA_PROJECT.ap14**: Main project file.
- **System**: Contains system-related files and directories such as `~PEData.3`, `~PEData.4`, `~PEData.5`, `PEData/`, `PEData.idx`, and `PEData.plf`.
- **TMP**: Temporary files.
- **UserFiles**: Directory for user files.
- **XRef**: Cross-reference files.

## Key Files

- **IM/HMI/C/0/Generates/pdata.tfz**: Contains various configuration settings and class IDs.
- **System/PEData/Meta/ChangeListConsumer/Siemens.Simatic.Lang.IPI.Target.xml**: XML file defining consumed objects for the target compiler.
- **System/PEData/Meta/ChangeListConsumer/Iecpl.xml**: XML file defining consumed objects for the IECPL.
- **IM/HMI/C/0/Generates/DownloadTask.xml**: XML file defining the download tasks for the project.
- **SCADA_PROJECT.ap14**: Main project file containing project data.