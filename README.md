# fs_LR_2_fsaverage

https://neurostars.org/t/problem-loading-surface-based-parcellation/16719

Convert labels in fs_LR space to fsaverage:

wb_command -label-resample Parcels_R.func.gii R.sphere.32k_fs_LR.surf.gii fs_R-to-fs_LR_fsaverage.R_LR.spherical_std.164k_fs_R.surf.gii BARYCENTRIC right.fsaverage164.label.gii

wb_command -label-resample Parcels_L.func.gii L.sphere.32k_fs_LR.surf.gii fs_L-to-fs_LR_fsaverage.L_LR.spherical_std.164k_fs_L.surf.gii BARYCENTRIC left.fsaverage164.label.gii

