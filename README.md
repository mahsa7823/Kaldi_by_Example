# Decoding

The input utterance to decode has 668 frames: U (U_feats.txt)

The decoding graph: HCLG (HCLG.pdf)

U o HCLG: 
 Decode(): creates the active_toks_ list for every frame (decode.pdf).
 
 GetRawLattice: create the state-level lattice base on the active_toks_ list (rawlat.pdf).
 
 Determinize(): determinized the raw lattice (detlat.pdf).

