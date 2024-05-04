<script lang="ts">
    export let title: string;
</script>

<div class="cell">
    <div class="card">
        <header class="card-header">
            <p class="card-header-title">{title}</p>
            <button class="card-header-icon" aria-label="more options">
                <span class="icon">
                    <i class="fa-solid fa-circle-info"></i>
                </span>
            </button>
        </header>
        <div class="card-content">
            <div class="content">
                <slot />
            </div>
        </div>
        <!-- <footer class="card-footer">
            <a href="#" class="card-footer-item">Save</a>
        </footer> -->
    </div>
</div>

<style>
    .cell {
        padding: 0.25rem;
    }
</style>
