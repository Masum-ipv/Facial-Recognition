
# FaceNet
FaceNet is a neural network that learns a mapping from face images to a compact Euclidean space where distances correspond to a measure of face similarity. That is to say, the more similar two face images are the lesser the distance between them.

# Triplet Loss
FaceNet uses a distinct loss method called Triplet Loss to calculate loss. Triplet Loss minimises the distance between an anchor and a positive, images that contain same identity, and maximises the distance between the anchor and a negative, images that contain different identities.

# Siamese Networks
Siamese networks consist of two identical neural networks, each with the same exact weights. First, each network take one of the two input images as input. Then, the outputs of the last layers of each network are sent to a function that determines whether the images contain the same identity.

