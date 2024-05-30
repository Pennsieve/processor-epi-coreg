FROM freesurfer/freesurfer:7.4.1

COPY license.txt /usr/local/freesurfer/license.txt
CMD [ "/bin/sh", "-c", "recon-all -s sub-RID0815 -i $INPUT_DIR/sub-RID0815_ses-research3Tv04_acq-3D_T1w.nii.gz -all -sd \"$OUTPUT_DIR\""]