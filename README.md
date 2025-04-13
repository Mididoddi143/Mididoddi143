<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout 
        android:orientation="vertical"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="16dp">

        <!-- Header -->
        <TextView
            android:id="@+id/tvWelcome"
            android:text="Welcome to XYZ Diagnostics"
            android:textSize="20sp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"/>

        <!-- Quick Actions -->
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:gravity="center"
            android:layout_marginTop="16dp">

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Book Test"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="View Reports"
                android:layout_marginStart="8dp"/>
        </LinearLayout>

        <!-- Popular Tests -->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Popular Tests"
            android:textSize="18sp"
            android:layout_marginTop="24dp"/>

        <ListView
            android:id="@+id/lvTests"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="8dp"/>
    </LinearLayout>
</ScrollView>