<script lang="ts">
    import Card from "./Card.svelte";
</script>


<Card title="2 - Select recipe units of measure">
    <div slot="tooltip" class="tooltip">
        <span
        class="icon has-tooltip-multiline has-tooltip-left"
        data-tooltip="Choose which unit of measure to use."
    >
        <i class="fa-solid fa-circle-info"></i>
    </span>
    </div>
    <div class="field">
        <div class="control">
            <label for="radio-percentage" class="radio">
                <input type="radio" name="unit" id="radio-percentage" checked />
                Percentages
            </label>
            <label for="radio-grams" class="radio">
                <input type="radio" name="unit" id="radio-grams" /> Grams
            </label>
            <label for="radio-kilos" class="radio">
                <input type="radio" name="unit" id="radio-kilos" /> Kilograms
            </label>
            <label for="radio-pounds" class="radio">
                <input type="radio" name="unit" id="radio-pounds" /> Pounds
            </label>
            <label for="radio-ounces" class="radio">
                <input type="radio" name="unit" id="radio-ounces" /> Ounces
            </label>
        </div>
        <div class="control">
            <label for="extra" class="radio">
                <input type="radio" name="extra" id="extra" /> FOOBAR
            </label>
        </div>
    </div>
</Card>
