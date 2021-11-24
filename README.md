# METAVERSE
Android
startActivityForResult(Meta.getStoryboardIntent(this, "7629cc1a-e435-4347-802e-4c4daa37df20"), 1000);
iOS (Swift)
Meta.shared.present(experience: MetaExperience(id: "7629cc1a-e435-4347-802e-4c4daa37df20"))
iOS (Objective C)
MetaExperience *experience = [[MetaExperience alloc] initWithId:@"7629cc1a-e435-4347-802e-4c4daa37df20"];
[[Meta shared] presentWithExperience: experience];
