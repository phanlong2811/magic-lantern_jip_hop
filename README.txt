EOSM 2.0.2 card files built from eosm-ux-async-gain-color-preview @ 4698313 (photo mode M gain shortcuts + MENU opens Canon INFO screen in photo M)
with gcc 13.2.1 (phone build). Known: ML FPS override + 5K anamorphic may give a garbage Framing preview with gcc13 builds.
Copy autoexec.bin to the card root and ML/modules/* to ML/modules/ together (remove other .mo). Keep ML/SETTINGS.
Only crop_rec.mo changed vs eosm-build-451-gcc13; autoexec.bin and EOSM_202.sym are identical.
