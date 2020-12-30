# Decoding

The input utterance to decode has 668 frames: U (U_feats.txt)

The decoding graph: HCLG (HCLG.pdf)

U o HCLG:

 Decode(): creates the active_toks_ list for every frame (decode.pdf).
 
 GetRawLattice: creates the state-level lattice based on the active_toks_ list (rawlat.pdf).
 
 Determinize(): determinize the raw lattice (detlat.pdf).

