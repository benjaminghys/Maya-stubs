# ✅ Maya Python API 2.0 Stub Progress

<p align="left"> <img src="https://komarev.com/ghpvc/?username=maya-stubs&label=Visitors&color=65c065&style=flat" alt="Page visits" /> </p>

**Total progress:** `125 / 299` classes complete.
![](https://geps.dev/progress/41?dangerColor=65c065&warningColor=65c065&successColor=65c065)

**Last Updated:** 2025-07-15

**Estimated number of unit tests:** ~8488¹

> This public repository tracks the ongoing development of **strict, manually unit-tested Python stubs** for Autodesk Maya’s Python API 2.0.
> These stubs provide **accurate type hints**, **correct argument signatures**, and are fully compatible with **static type checkers** like MyPy.

---

## 🎯 Project Goals

- Deliver strict but **accurate Maya stubs** — no autogenerated junk.
- Each class and function is **individually verified** through unit testing in a real Maya 2022.5 environment.
- Designed to support **Python 3.7+** (later versions will match Maya's interpreter versions).
- Once full coverage is reached for Maya 2022, **more Maya versions will follow**.
- Depending on demand, stubs will be created in this order: 2022, 2023, 2024, 2025, 2026.

---

## 🛠️ What to Expect

- **Progress is tracked live** in this README.
- New classes are completed regularly — this is a solo project with **weekly updates**.
- Once v1.0 is complete, **distribution details will be announced here**.
- Pricing will remain **accessible for individuals and freelancers**, with tiered licensing for studios.

---

## ⭐ How You Can Support

- **Star this repository** to follow development and get notified when releases drop.
- Share this project with fellow Technical Artists or Maya Python scripters who demand better tooling.
- Your support makes a huge difference for a one-person dev shop building tools for the community.

---

## 🔍 Module Progress

### `maya.api.OpenMaya`

![](https://geps.dev/progress/80?dangerColor=65c065&warningColor=65c065&successColor=65c065)

<details>
<summary><strong>125 / 155 classes complete</strong></summary>

- ✅ `MAngle`
- ✅ `MArgDatabase`
- ✅ `MArgList`
- ✅ `MArgParser`
- ✅ `MArrayDataBuilder`
- ✅ `MArrayDataHandle`
- ✅ `MAttributeIndex`
- ✅ `MAttributePattern`
- ✅ `MAttributeSpec`
- ✅ `MAttributeSpecArray`
- ✅ `MBoundingBox`
- ✅ `MCallbackId`
- ✅ `MCallbackIdArray`
- ✅ `MCameraMessage`
- ✅ `MColor`
- ✅ `MColorArray`
- ✅ `MCommandMessage`
- ✅ `MConditionMessage`
- ✅ `MContainerMessage`
- ✅ `MDAGDrawOverrideInfo`
- ✅ `MDGContext`
- ✅ `MDGMessage`
- ✅ `MDGModifier`
- ✅ `MDagMessage`
- ✅ `MDagModifier`
- ✅ `MDagPath`
- ✅ `MDagPathArray`
- ✅ `MDataBlock`
- ✅ `MDataHandle`
- ✅ `MDistance`
- ✅ `MDoubleArray`
- ✅ `MEulerRotation`
- ✅ `MEvaluationNode`
- ✅ `MEvaluationNodeIterator`
- ✅ `MEventMessage`
- ✅ `MExternalContentInfoTable`
- ✅ `MExternalContentLocationTable`
- ✅ `MFileObject`
- ✅ `MFloatArray`
- ✅ `MFloatMatrix`
- ✅ `MFloatPoint`
- ✅ `MFloatPointArray`
- ✅ `MFloatVector`
- ✅ `MFloatVectorArray`
- ✅ `MFn`
- ✅ `MFnAttribute`
- ✅ `MFnBase`
- ✅ `MFnCamera`
- ✅ `MFnComponent`
- ✅ `MFnComponentListData`
- ✅ `MFnCompoundAttribute`
- ✅ `MFnContainerNode`
- ✅ `MFnDagNode`
- ✅ `MFnData`
- ✅ `MFnDependencyNode`
- ⬜ `MFnDoubleArrayData`
- ✅ `MFnDoubleIndexedComponent`
- ✅ `MFnEnumAttribute`
- ✅ `MFnGenericAttribute`
- ⬜ `MFnGeometryData`
- ⬜ `MFnIntArrayData`
- ✅ `MFnLightDataAttribute`
- ⬜ `MFnMatrixArrayData`
- ✅ `MFnMatrixAttribute`
- ⬜ `MFnMatrixData`
- ✅ `MFnMesh`
- ✅ `MFnMeshData`
- ✅ `MFnMessageAttribute`
- ✅ `MFnNumericAttribute`
- ✅ `MFnNumericData`
- ✅ `MFnNurbsCurve`
- ⬜ `MFnNurbsCurveData`
- ✅ `MFnNurbsSurface`
- ⬜ `MFnNurbsSurfaceData`
- ✅ `MFnPlugin`
- ✅ `MFnPluginData`
- ⬜ `MFnPointArrayData`
- ✅ `MFnReference`
- ✅ `MFnSet`
- ✅ `MFnSingleIndexedComponent`
- ⬜ `MFnStringArrayData`
- ⬜ `MFnStringData`
- ✅ `MFnTransform`
- ✅ `MFnTripleIndexedComponent`
- ✅ `MFnTypedAttribute`
- ⬜ `MFnUInt64ArrayData`
- ✅ `MFnUnitAttribute`
- ⬜ `MFnVectorArrayData`
- ✅ `MGlobal`
- ✅ `MImage`
- ✅ `MInt64Array`
- ✅ `MIntArray`
- ⬜ `MItCurveCV`
- ⬜ `MItDag`
- ⬜ `MItDependencyGraph`
- ⬜ `MItDependencyNodes`
- ⬜ `MItGeometry`
- ⬜ `MItMeshEdge`
- ⬜ `MItMeshFaceVertex`
- ⬜ `MItMeshPolygon`
- ⬜ `MItMeshVertex`
- ⬜ `MItSelectionList`
- ⬜ `MItSurfaceCV`
- ⬜ `MIteratorType`
- ✅ `MLockMessage`
- ✅ `MMatrix`
- ✅ `MMatrixArray`
- ✅ `MMeshIntersector`
- ✅ `MMeshIsectAccelParams`
- ✅ `MMeshSmoothOptions`
- ✅ `MMessage`
- ✅ `MModelMessage`
- ✅ `MNamespace`
- ✅ `MNodeClass`
- ✅ `MNodeMessage`
- ✅ `MObject`
- ✅ `MObjectArray`
- ✅ `MObjectHandle`
- ✅ `MObjectSetMessage`
- ✅ `MPlane`
- ✅ `MPlug`
- ✅ `MPlugArray`
- ✅ `MPoint`
- ✅ `MPointArray`
- ✅ `MPointOnMesh`
- ✅ `MPolyMessage`
- ✅ `MPxAttributePatternFactory`
- ⬜ `MPxCommand`
- ⬜ `MPxData`
- ⬜ `MPxGeometryData`
- ⬜ `MPxGeometryIterator`
- ⬜ `MPxNode`
- ⬜ `MPxSurfaceShape`
- ✅ `MQuaternion`
- ✅ `MRampAttribute`
- ✅ `MRichSelection`
- ✅ `MSceneMessage`
- ✅ `MSelectionList`
- ✅ `MSelectionMask`
- ✅ `MSpace`
- ✅ `MSyntax`
- ✅ `MTime`
- ✅ `MTimeArray`
- ✅ `MTimerMessage`
- ✅ `MTransformationMatrix`
- ✅ `MTypeId`
- ✅ `MURI`
- ✅ `MUint64Array`
- ✅ `MUintArray`
- ✅ `MUserData`
- ✅ `MUserEventMessage`
- ✅ `MUuid`
- ✅ `MVector`
- ✅ `MVectorArray`
- ✅ `MWeight`

</details>


### `maya.api.OpenMayaAnim`

![](https://geps.dev/progress/0?dangerColor=65c065&warningColor=65c065&successColor=65c065)

<details>
<summary><strong>0 / 12 classes complete</strong></summary>

- ⬜ `MAnimControl`
- ⬜ `MAnimCurveChange`
- ⬜ `MAnimCurveClipboard`
- ⬜ `MAnimCurveClipboardItem`
- ⬜ `MAnimCurveClipboardItemArray`
- ⬜ `MAnimMessage`
- ⬜ `MAnimUtil`
- ⬜ `MFnAnimCurve`
- ⬜ `MFnGeometryFilter`
- ⬜ `MFnIkJoint`
- ⬜ `MFnSkinCluster`
- ⬜ `MFnWeightGeometryFilter`

</details>


### `maya.api.OpenMayaRender`

![](https://geps.dev/progress/0?dangerColor=65c065&warningColor=65c065&successColor=65c065)

<details>
<summary><strong>0 / 87 classes complete</strong></summary>

- ⬜ `MAttributeParameterMapping`
- ⬜ `MAttributeParameterMappingList`
- ⬜ `MBlendState`
- ⬜ `MBlendStateDesc`
- ⬜ `MCameraOverride`
- ⬜ `MClearOperation`
- ⬜ `MColorManagementUtilities`
- ⬜ `MComponentDataIndexing`
- ⬜ `MComponentDataIndexingList`
- ⬜ `MDepthNormalizationDescription`
- ⬜ `MDepthStencilState`
- ⬜ `MDepthStencilStateDesc`
- ⬜ `MDrawContext`
- ⬜ `MDrawRegistry`
- ⬜ `MFragmentManager`
- ⬜ `MFrameContext`
- ⬜ `MGeometry`
- ⬜ `MGeometryExtractor`
- ⬜ `MGeometryIndexMapping`
- ⬜ `MGeometryRequirements`
- ⬜ `MGeometryUtilities`
- ⬜ `MHUDRender`
- ⬜ `MIndexBuffer`
- ⬜ `MIndexBufferDescriptor`
- ⬜ `MIndexBufferDescriptorList`
- ⬜ `MInitContext`
- ⬜ `MInitFeedback`
- ⬜ `MIntersection`
- ⬜ `MLightParameterInformation`
- ⬜ `MPassContext`
- ⬜ `MPresentTarget`
- ⬜ `MPxComponentConverter`
- ⬜ `MPxDrawOverride`
- ⬜ `MPxGeometryOverride`
- ⬜ `MPxImagePlaneOverride`
- ⬜ `MPxIndexBufferMutator`
- ⬜ `MPxPrimitiveGenerator`
- ⬜ `MPxShaderOverride`
- ⬜ `MPxShadingNodeOverride`
- ⬜ `MPxSubSceneOverride`
- ⬜ `MPxSurfaceShadingNodeOverride`
- ⬜ `MPxVertexBufferGenerator`
- ⬜ `MPxVertexBufferMutator`
- ⬜ `MQuadRender`
- ⬜ `MRasterizerState`
- ⬜ `MRasterizerStateDesc`
- ⬜ `MRenderItem`
- ⬜ `MRenderItemList`
- ⬜ `MRenderOperation`
- ⬜ `MRenderOverride`
- ⬜ `MRenderParameters`
- ⬜ `MRenderProfile`
- ⬜ `MRenderTarget`
- ⬜ `MRenderTargetAssignment`
- ⬜ `MRenderTargetDescription`
- ⬜ `MRenderTargetManager`
- ⬜ `MRenderUtilities`
- ⬜ `MRenderer`
- ⬜ `MSamplerState`
- ⬜ `MSamplerStateDesc`
- ⬜ `MSceneRender`
- ⬜ `MSelectionContext`
- ⬜ `MSelectionInfo`
- ⬜ `MShaderCompileMacro`
- ⬜ `MShaderInstance`
- ⬜ `MShaderManager`
- ⬜ `MStateManager`
- ⬜ `MStencilOpDesc`
- ⬜ `MSubSceneContainer`
- ⬜ `MSubSceneContainerIterator`
- ⬜ `MSwatchRenderBase`
- ⬜ `MTargetBlendDesc`
- ⬜ `MTexture`
- ⬜ `MTextureAssignment`
- ⬜ `MTextureDescription`
- ⬜ `MTextureManager`
- ⬜ `MTextureUpdateRegion`
- ⬜ `MUIDrawManager`
- ⬜ `MUniformParameter`
- ⬜ `MUniformParameterList`
- ⬜ `MUserRenderOperation`
- ⬜ `MVaryingParameter`
- ⬜ `MVaryingParameterList`
- ⬜ `MVertexBuffer`
- ⬜ `MVertexBufferArray`
- ⬜ `MVertexBufferDescriptor`
- ⬜ `MVertexBufferDescriptorList`

</details>


### `maya.api.OpenMayaUI`

![](https://geps.dev/progress/0?dangerColor=65c065&warningColor=65c065&successColor=65c065)

<details>
<summary><strong>0 / 45 classes complete</strong></summary>

- ⬜ `M3dView`
- ⬜ `MCursor`
- ⬜ `MDrawData`
- ⬜ `MDrawInfo`
- ⬜ `MDrawProperties`
- ⬜ `MDrawRequest`
- ⬜ `MEvent`
- ⬜ `MFnCircleSweepManip`
- ⬜ `MFnCurveSegmentManip`
- ⬜ `MFnDirectionManip`
- ⬜ `MFnDiscManip`
- ⬜ `MFnDistanceManip`
- ⬜ `MFnFreePointTriadManip`
- ⬜ `MFnManip3D`
- ⬜ `MFnPointOnCurveManip`
- ⬜ `MFnPointOnSurfaceManip`
- ⬜ `MFnRotateManip`
- ⬜ `MFnScaleManip`
- ⬜ `MFnStateManip`
- ⬜ `MFnToggleManip`
- ⬜ `MHWShaderSwatchGenerator`
- ⬜ `MManipData`
- ⬜ `MMaterial`
- ⬜ `MMaterialArray`
- ⬜ `MPaintMessage`
- ⬜ `MPanelCanvas`
- ⬜ `MPanelCanvasInfo`
- ⬜ `MPxContext`
- ⬜ `MPxContextCommand`
- ⬜ `MPxDragAndDropBehavior`
- ⬜ `MPxHardwareShader`
- ⬜ `MPxHwShaderNode`
- ⬜ `MPxLocatorNode`
- ⬜ `MPxManipContainer`
- ⬜ `MPxManipulatorNode`
- ⬜ `MPxSelectionContext`
- ⬜ `MPxSurfaceShapeUI`
- ⬜ `MPxToolCommand`
- ⬜ `MSelectInfo`
- ⬜ `MTextureEditorDrawInfo`
- ⬜ `MTimeSliderCustomDrawManager`
- ⬜ `MTimeSliderDrawPrimitive`
- ⬜ `MUiMessage`
- ⬜ `RenderParameters`
- ⬜ `ShaderContext`

</details>

## 📦 Sample Stub

Here's an example of a fully tested, strict Python stub for `maya.api.OpenMaya.MArgList`.
These stubs aim to match Maya's internal API behavior as closely as possible.

<details>
<summary><strong>Click to expand</strong></summary>

> [!NOTE]
> This stub is meant to work with Python 3.7+, positional-only arguments were introduced in Python 3.8.
> Therefore, positional-only arguments have been prefixed with `__`

```python
from typing import overload, Final, Union, Self, List, Optional
from maya.api.OpenMaya import MArgList, MAngle, MDistance, MPoint, MTime, MVector, MDoubleArray, MIntArray, MMatrix


class MArgList:
    kInvalidArgIndex: Final[int] = -1

    @overload
    def __init__(self) -> None: ...
    @overload
    def __init__(self, __src: MArgList) -> None: ...
    __doc__: Final[str] = "Argument list for passing to commands."
    def __len__(self) -> int: ...
    def addArg(self, __value: Union[bool, int, float, str, MAngle, MDistance, MPoint, MTime, MVector]) -> Self: ...
    def asAngle(self, __index: int) -> MAngle: ...
    def asBool(self, __index: int) -> bool: ...
    def asDistance(self, __index: int) -> MDistance: ...
    def asDouble(self, __index: int) -> float: ...
    def asDoubleArray(self, __index: int) -> MDoubleArray: ...
    def asFloat(self, __index: int) -> float: ...
    def asInt(self, __index: int) -> int: ...
    def asIntArray(self, __index: int) -> MIntArray: ...
    def asMatrix(self, __index: int) -> MMatrix: ...
    def asPoint(self, __index: int, numElements: int=3) -> MPoint: ...
    def asString(self, __index: int) -> str: ...
    def asStringArray(self, __index: int) -> List[str]: ...
    def asTime(self, __index: int) -> MTime: ...
    def asVector(self, __index: int, numElements: int=3) -> MVector: ...
    def flagIndex(self, __shortFlag: str, longFlag: Optional[str]=None) -> int: ...
    def lastArgUsed(self) -> int: ...
```

</details>

---

¹ Does _**not**_ include shared/inherited tests across similar types (e.g., M*Array classes).

---

Thanks for following the journey!
