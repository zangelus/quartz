It is the compressed "essence" of the input. 
It is the "abstract" representation of the input

Example: 
1) [[Autoencoders]]
	1) Encoder: Maps input to latent space
	2) Decoder: Maps latent space to reconstruct the input.
2) [[Bert]]
	1) Each word in "I like coffee" is converted into a dense vector - a point in latent space. 
	   "coffee" → [0.31, -0.14, 0.88, ..., 0.05]  # A dense vector in latent space. 
	   It **encodes them into dense vectors** that live in this high-dimensional, abstract space.
3) 
	