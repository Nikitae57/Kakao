//[kakao](../../../index.md)/[io.github.kakaocup.kakao.pager2](../index.md)/[KViewPagerItemTypeBuilder](index.md)/[itemType](item-type.md)



# itemType  
[androidJvm]  
Content  
inline fun <[T](item-type.md) : [KViewPagerItem](../-k-view-pager-item/index.md)<*>> [itemType](item-type.md)(noinline provideItem: (Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>) -> [T](item-type.md))  
More info  


Adds entry that helps KViewPager2 to automatically build child views



To make it work, you need to pass here function (lambda, constructor), that takes matcher and returns instance of your item type. In this case, matcher actually matches root view of your adapter item.



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.pager2/KViewPagerItemTypeBuilder/itemType/#kotlin.Function1[org.hamcrest.Matcher[android.view.View],TypeParam(bounds=[io.github.kakaocup.kakao.pager2.KViewPagerItem[*]])]/PointingToDeclaration/"></a>provideItem| <a name="io.github.kakaocup.kakao.pager2/KViewPagerItemTypeBuilder/itemType/#kotlin.Function1[org.hamcrest.Matcher[android.view.View],TypeParam(bounds=[io.github.kakaocup.kakao.pager2.KViewPagerItem[*]])]/PointingToDeclaration/"></a><br><br>Function that takes matcher of item's root view and returns instance of item view<br><br>|
  
  


