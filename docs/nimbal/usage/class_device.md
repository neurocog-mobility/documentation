# The 'Device' class

The `Device` class is used to store raw device data.

## Class directory
### Properties
#### header
Device collection metadata:

*study_code subject_id, coll_id, name, sex, birthdate, patient_additional, start_datetime, config_datetime, technician, device_type, device_id, device_location, recording_additional*

#### signal_headers
List of dictionaries holding metadata for each device channel:

*label, transducer, dimension, sample_rate, physical_max, physical_min, digital_max, digital_min, prefilter*

#### signals
List of raw data signals for each device channel.

### Methods

#### autocal()
#### crop()
#### deidentify()
#### export_edf()
#### get_day_idxs()
#### get_idxs_from_date()
#### get_signal_index()
#### get_timestamps()
#### import_axivity()
#### import_bittium()
#### import_edf()
#### import_geneactiv()
#### rotate_z()
#### sync()