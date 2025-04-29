For the final project of this class we had to find (a) dataset(s) we had not used yet and use attacks/defenses we also had not implimented yet. The dataset I picked was the EuroSAT dataset in the HuggingFace library, and the attacks I picked where Linf DeepFool Attack, HopSkipJump Attack, One-Pixel Attack, and the Linf Additive Uniform Noise Attack.

Unfortunately I was getting contradictory errors when implimenting the One-Pixel attack and as such switched it to the Binary Search Contrast Reduction Attack.

The initial model had an accuracy of 93%, and the Linf DeepFool Attack crushed the model giving it an accuracy of 0%, however the other three attacks; HopSkipJump, Binary Search Contrast Reduction, and One-Pixel, all had little to no effect on the model.
