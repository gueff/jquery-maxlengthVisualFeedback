# jquery-maxlengthVisualFeedback

dynamically visualize a current input char consumption considering the related maxlength attribute value of HTML5 `<form>` input elements such as `<input>` and `<textarea>` with a Progress-Bar using jQuery.

My Solution shows a progressbar beneath an input element illustrating in realtime how much of the assigned size defined by the element's maxlength (or data-maxlength) attribute has already been used. Per default it appears if current input is about >=50% of the assigned maxlength (you can change this).

It shows three different coloured sections:

- sectionA 50-69% (lightblue)
- sectionB 70-99% (orange)
- sectionC 100% (lightcoral)

The section colors you style by CSS. The section sizes you define by JS (see Modifying).

---

For Documentation and Examples, please see my Article [dynamic visualization of consumption of chars in input elements with jQuery in relation to the value of a maxlength attribute](https://blog.ueffing.net/post/2016/03/14/dynamic-visualization-of-consumption-of-chars-in-input-elements-with-jquery-in-relation-to-the-value-of-a-maxlength-attribute/) on https://blog.ueffing.net
