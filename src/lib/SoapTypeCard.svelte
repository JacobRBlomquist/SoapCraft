<script lang="ts">
    import Card from "./Card.svelte";
</script>

<Card title="1 - Liquid or Solid soap recipe?">
    <div slot="tooltip" class="tooltip">
        <span
            class="icon has-tooltip-multiline has-tooltip-left"
            data-tooltip="Choose which type of lye to use. Usually NaOH is used for solid
        soap, and KOH is used for liquid soap. Be sure to choose the correct
        one, as this will affect how much lye is needed to saponify the
        various oils."
        >
            <i class="fa-solid fa-circle-info"></i>
        </span>
    </div>
    <div class="field">
        <div class="control">
            <label for="radio-naoh" class="radio">
                <input
                    type="radio"
                    name="liquid-or-solid"
                    id="radio-naoh"
                    checked
                />
                Solid Soap - using
                <strong>NaOH</strong> (Sodium Hydroxide)
            </label>
        </div>
        <div class="control">
            <label for="radio-koh" class="radio">
                <input type="radio" name="liquid-or-solid" id="radio-koh" />
                Liquid Soap - using
                <strong>KOH</strong> (Potassium Hydroxide)
            </label>
        </div>
    </div>
</Card>
