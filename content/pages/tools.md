---
content_type: page
description: Software and hardware tools required for the lab work.
hide_download: true
hide_download_original: null
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 713b619d-ad80-8a4a-69c3-88a205f93170
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Software
--------

The 2.672 lab uses the ME computer network system under Window NT. Computer software packages have been installed in the lab computers for data acquisition, data processing, and word processing. The following is a brief overview of these packages.

1.  **LabView**: There are several icons here: CHART, WAVEFORM and VBENCH. **CHART is the package we use the most**; it is a general data logging program and displays the data on the fly. You can select which segment of the data you want to store afterwards. WAVEFORM acquires data in the usual way but you cannot display the data until the whole set is taken. VBENCH is a data acquisition virtual bench, which provides simulated oscilloscope, signal generators etc.
2.  **MATLAB**: Data processing, data plotting, and numerical simulation software. It has built-in programs for solving differential equations, curve fitting, and signal analysis. Below, you can find scripts developed for various experiments in this course.
3.  **Microsoft Word**: Word processing software.
4.  **Microsoft Excel**: Spreadsheet software.
5.  **Microsoft PowerPoint**: Presentation software.
6.  **FTP**: There is an icon based file transfer program for porting files between the lab computer and the MIT server.

Supporting Files
----------------

The following MATLAB '.m' files may be useful to you as you massage the data you collect in the various experiments. If you develop other '.m' files that you think would be useful in this course, please send them to the course instructors.

fitplot.m ({{% resource_link 1da5c2ac-9df4-754f-c7d3-1ed2a3576847 "M" %}})  
Fits n degree polynomial to input vectors xin, yin; fit coefficients in coeff.

getdata.m ({{% resource_link ce825e55-6d79-a2c1-f147-9e27aacceca3 "M" %}})  
Utility to get the time and voltage trace from a data file.

powerfit.m ({{% resource_link b2b9e120-fadf-e09b-fd95-c0d5de50ce12 "M" %}})  
Least square fit of data using linear combination of powers.

pwrspect.m ({{% resource_link e9c0cb83-cdf4-000f-7865-43346336178b "M" %}})  
Analysis of power spectrum.

steam\_p.m ({{% resource_link 51da944b-9850-0912-255e-0f7c80f4dfb0 "M" %}})  
Saturation properties for H{{< sub "2" >}}O; output saturation pressure.

steam\_t.m ({{% resource_link 6c228ef3-629a-6499-2b44-03f8d3a9ec89 "M" %}})  
Saturation properties for H{{< sub "2" >}}O; output saturation temperature.

fig\_h.m ({{% resource_link 5e9c850f-e43c-b044-88b5-4465d85f4c79 "M" %}})  
Utility to make MATLAB plots better for importing into reports.

H2Oprop.m ({{% resource_link 71329adf-5ad1-20db-51bb-680d5f0b8d1a "M" %}})  
Thermodynamic properties for water; general-purpose function

A brief guide to MATLAB as used in this course is provided: ({{% resource_link 5440e508-a101-846d-7538-e729eb3e10db "PDF" %}})