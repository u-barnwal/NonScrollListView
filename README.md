[![](https://jitpack.io/v/u-barnwal/NonScrollListView.svg)](https://jitpack.io/#u-barnwal/NonScrollListView)
# NonScrollListView

ListView that grows its height based on chlid height and count.


## Implementation
**Step 1:** Add to project level build.gradle

    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

**Step 2:** Add to app level build.gradle

	dependencies {
	    implementation 'com.github.u-barnwal:NonScrollListView:VERSION'
	}
## How to use
**Step 1:** Create view

    <com.isolpro.library.nonscrolllistview.NonScrollListView  
	  android:layout_width="match_parent"  
	  android:layout_height="wrap_content" />
**Step 2:** Use it like a normal ListView


## Features

 - Used exactly like ListView
 - Can be used inside a ScrollView
 - Support all list adapters
 - Fully adaptive

## Links
 - Live example: https://transactionslistlite.isolpro.in
