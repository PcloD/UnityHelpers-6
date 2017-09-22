# UnityHelpers
Quick classes and functions to help out personal Unity development

# SerializeFieldAsAttribute
Custom attribute which allows the assignment of an alias to serialized fields in the Unity Editor.
Call the usual [SerializeField] attribute, and add [SerializeFieldAs("StringToUseAsAlias")] above that.
Takes in 1 string parameter which displays in the Inspector panel without renaming the reference to the field in the code
