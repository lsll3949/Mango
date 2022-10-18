# Mango
<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/tableLayout1"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TableRow>
        <EditText
            android:layout_weight="1"
            android:id="@+id/Edit1"
            android:layout_span="5"
            android:hint="숫자1입력"/>
    </TableRow>

    <TableRow>
        <EditText
            android:layout_weight="1"
            android:id="@+id/Edit2"
            android:layout_span="5"
            android:hint="숫자2입력"/>
    </TableRow>

    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum0"
            android:text="0" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum1"
            android:text="1" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum2"
            android:text="2" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum3"
            android:text="3" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum4"
            android:text="4" />
    </TableRow>

    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum5"
            android:text="5" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum6"
            android:text="6" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum7"
            android:text="7" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum8"
            android:text="8" />
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnNum9"
            android:text="9" />
    </TableRow>
    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnAdd"
            android:layout_margin="5dp"
            android:layout_span="5"
            android:text="더하기" />
    </TableRow>

    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnSub"
            android:layout_margin="5dp"
            android:layout_span="5"
            android:text="빼기" />
    </TableRow>
    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnMul"
            android:layout_margin="5dp"
            android:layout_span="5"
            android:text="곱하기" />
    </TableRow>
    <TableRow>
        <Button
            android:layout_weight = "1"
            android:id="@+id/BtnDiv"
            android:layout_margin="5dp"
            android:layout_span="5"
            android:text="나누기" />
    </TableRow>
    <TableRow>
        <TextView
            android:id="@+id/TextResult"
            android:layout_margin="5dp"
            android:layout_span="5"
            android:text="계산 결과 : "
            android:textColor="#FF0000"
            android:textSize="20dp" />
    </TableRow>





</TableLayout>
