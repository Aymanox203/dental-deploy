<script>
    const inputRow1 = [17, 16, 15, 14, 13, 12, 11, 21, 22, 23, 24, 25, 26, 27]
    const inputRow2 = [47, 46, 45, 44, 43, 42, 41, 31, 32, 33, 34, 35, 36, 37]
</script>

<div class="teeth-grid">
    <!-- First Row: Tooth IDs (upper teeth) -->
    <div class="teeth-cell">17</div>
    <div class="teeth-cell">16</div>
    <div class="teeth-cell">15</div>
    <div class="teeth-cell">14</div>
    <div class="teeth-cell">13</div>
    <div class="teeth-cell">12</div>
    <div class="teeth-cell">11</div>
    <div class="teeth-cell">21</div>
    <div class="teeth-cell">22</div>
    <div class="teeth-cell">23</div>
    <div class="teeth-cell">24</div>
    <div class="teeth-cell">25</div>
    <div class="teeth-cell">26</div>
    <div class="teeth-cell">27</div>

    <!-- Second Row: Values for upper teeth -->
    {#each inputRow1 as Col}
    <div class="teeth-cell">
        <div class="sub-grid">
            <input type="text" name="value_18_1" class="sub-input" placeholder="1">
            <input type="text" name="value_18_2" class="sub-input" placeholder="2">
            <input type="text" name="value_18_3" class="sub-input" placeholder="3">
            <input type="text" name="value_18_4" class="sub-input" placeholder="4">
            <input type="text" name="value_18_5" class="sub-input" placeholder="5">
            <input type="text" name="value_18_6" class="sub-input" placeholder="6">
        </div>
    </div>
    {/each}

    

    <!-- Third Row: Tooth IDs (lower teeth) -->
    <div class="teeth-cell">47</div>
    <div class="teeth-cell">46</div>
    <div class="teeth-cell">45</div>
    <div class="teeth-cell">44</div>
    <div class="teeth-cell">43</div>
    <div class="teeth-cell">42</div>
    <div class="teeth-cell">41</div>
    <div class="teeth-cell">31</div>
    <div class="teeth-cell">32</div>
    <div class="teeth-cell">33</div>
    <div class="teeth-cell">34</div>
    <div class="teeth-cell">35</div>
    <div class="teeth-cell">36</div>
    <div class="teeth-cell">37</div>

    <!-- Fourth Row: Values for lower teeth -->
    {#each inputRow1 as Col}
    <div class="teeth-cell">
        <div class="sub-grid">
            <input type="text" name="value_18_1" class="sub-input" placeholder="1">
            <input type="text" name="value_18_2" class="sub-input" placeholder="2">
            <input type="text" name="value_18_3" class="sub-input" placeholder="3">
            <input type="text" name="value_18_4" class="sub-input" placeholder="4">
            <input type="text" name="value_18_5" class="sub-input" placeholder="5">
            <input type="text" name="value_18_6" class="sub-input" placeholder="6">
        </div>
    </div>
    {/each}
</div>